https://help.obsidian.md/callouts
# Obsidian Callout Test Sheet

This file displays all built-in callout types and syntax variations to test themes and CSS snippets.

## Titles

> [!tip] Callouts can have custom titles
> Like this one.

 ```
> [!tip] Callouts can have custom titles
> Like this one.
 ```

> [!tip] Title-only callout
```
> [!tip] Title-only callout
```


## Folding

Foldable callouts are created by adding a plus or minus immediately after the type identifier without spaces. Default behavior: plus sign = expanded, minus sign = collapsed

> [!faq]- Are callouts foldable?
> Yes! In a foldable callout, the contents are hidden when the callout is collapsed.

```
> [!faq]- Are callouts foldable?
> Yes! In a foldable callout, the contents are hidden when the callout is collapsed.
```

## Nesting
Callouts can be nested in multiple levels and can be combined with folding.

> [!question] Can callouts be nested?
> > [!todo] Yes!, they can.
> > > [!example]  You can even use multiple layers of nesting.

```
> [!question] Can callouts be nested?
> > [!todo] Yes!, they can.
> > > [!example]  You can even use multiple layers of nesting.
```

---

## Standard Callout Types

This section covers all 13 default callout types and their aliases.

### Note [!note]
**Aliases:** (none)

> [!note]
> Lorem ipsum dolor sit amet
---

```markdown
> [!note]
> This is a standard note callout.
```

### Abstract [!abstract] 
**Aliases:** `summary` `tldr`

> [!abstract]
> Lorem ipsum dolor sit amet

#### Summary [!summary]

> [!summary]
> Lorem ipsum dolor sit amet

#### tldr [!tldr]

> [!tldr]
> Lorem ipsum dolor sit amet

## Info [!info]
**Aliases:** (none)

> [!info]
> Lorem ipsum dolor sit amet

## Todo [!todo]
**Aliases:** (none)

> [!todo]
> Lorem ipsum dolor sit amet

## Tip [!tip]
**Aliases:** `hint`, `important`
> [!tip]
> Lorem ipsum dolor sit amet

### Hint [!hint]

> [!hint]
> Lorem ipsum dolor sit amet
### Important [!important]

> [!important]
> Lorem ipsum dolor sit amet

## Success [!success]
**Aliases:** `check`, `done`

> [!success]
> Lorem ipsum dolor sit amet

### Check [!check]

> [!check]
> Lorem ipsum dolor sit amet
### Done [!done]

> [!done]
> Lorem ipsum dolor sit amet

## Question [!question]
**Aliases:** `help`, `faq`

> [!question]
> Lorem ipsum dolor sit amet

### Help [!help]
**Aliases:** `caution`, `attention`

> [!help]
> Lorem ipsum dolor sit amet

### FAQ [!faq]

> [!faq]
> Lorem ipsum dolor sit amet

## Warning [!warning]
**Aliases:** `caution`, `attention`

> [!warning]
> Lorem ipsum dolor sit amet

### Caution [!caution]

> [!caution]
> Lorem ipsum dolor sit amet

### Attention [!attention]

> [!attention]
> Lorem ipsum dolor sit amet


## Failure [!failure]
**Aliases:** `fail`, `missing`

> [!failure]
> Lorem ipsum dolor sit amet

### Fail [!fail]

> [!fail]
> Lorem ipsum dolor sit amet

### Missing [!missing]

> [!missing]
> Lorem ipsum dolor sit amet

## Danger [!danger]
**Aliases:** `error`

> [!danger]
> Lorem ipsum dolor sit amet

### Error [!error]

> [!error]
> Lorem ipsum dolor sit amet

## Bug [!bug]
**Aliases:** (none)

> [!bug]
> Lorem ipsum dolor sit amet

## Example [!example]
**Aliases:** (none)

> [!example]
> Lorem ipsum dolor sit amet

## Quote [!quote]
**Aliases:** (none)

> [!quote]
> Lorem ipsum dolor sit amet

### Cite [!cite]
**Aliases:** (none)

> [!cite]
> Lorem ipsum dolor sit amet
