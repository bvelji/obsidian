
# Gather incomplete tasks from Tasks notes in folder
- Includes Subtasks where a completed subtask is not removed until the parent task is done. If a parent task is completed with incomplete subtasks, the subtasks are shown as unnested tasks.
- Sorts by priority icons used by Tasker plugin
  
````
```dataview
TASK
FROM "Tasks"
WHERE !completed


FLATTEN 
  choice(contains(text, "🔺"), 1, 
  choice(contains(text, "⏫"), 2, 
  choice(contains(text, "🔼"), 3, 
  choice(contains(text, "🔽"), 5, 
  choice(contains(text, "⏬️"), 6, 4))))) 
as priority 

SORT priority
```
````
