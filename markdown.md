# Markdown Basics
=======================================
=======================================

## Headings
=======================================
```
# The largest heading (an <h1> tag)
## The second largest heading (an <h2> tag)
###### The 6th largest heading (an <h6> tag)
```
#h1
##h2
######h6

## Horizontal Rules
=======================================
```
---

* * *

- - - - 
```

---

* * *

- - - - 


## Blockquotes
=======================================
```
In the words of Abraham Lincoln:
> Pardon my frenchch
>> Pardon my frenchch
```
In the words of Abraham Lincoln:
>Pardon my frenchch
>> Pardon my frenchch

## Styling text
=======================================

`*This text will be italic*`  *italic*

`**This text will be bold**`  **bold**

`_This text will be italic_`  _italic_

`__This text will be bold__`  __bold__

Both bold and italic can use either a * or an _ around the text for styling. This allows you to combine both bold and italic if needed.

```
**Everyone _must_ attend the meeting at 5 o'clock today.**

**Everyone *must* attend the meeting at 5 o'clock today.**

```

**Everyone _must_ attend the meeting at 5 o'clock today.**

**Everyone *must* attend the meeting at 5 o'clock today.**

## Lists
=======================================

### Unordered lists
----------------------------------------------

You can make an unordered list by preceding list items with either a `*` or a `-`.
```
*  Item
*  Item
*  Item

- Item
- Item
- Item
```
*  Item
*  Item
*  Item

- Item
- Item
- Item

### Ordered lists
----------------------------------

You can make an ordered list by preceding list items with a number.
```
1. Item 1
2. Item 2
3. Item 3
```
1. Item 1
2. Item 2
3. Item 3

### Nested lists
--------------------------

You can create nested lists by indenting list items by two spaces.
```
1. Item 1
  1. A corollary to the above item.
  2. Yet another point to consider.
2. Item 2
  * A corollary that does not need to be ordered.
    * This is indented four spaces, because it's two spaces further than the item above.
    * You might want to consider making a new list.
3. Item 3
```
1. Item 1
  1. A corollary to the above item.
  2. Yet another point to consider.
2. Item 2
  * A corollary that does not need to be ordered.
    * This is indented four spaces, because it's two spaces further than the item above.
    * You might want to consider making a new list.
3. Item 3

## Code formatting
=======================================

### Inline formats
---------------------------

Use single backticks (`) to format text in a special monospace format. Everything within the backticks appear as-is, with no other special formatting.

```Here's an idea: why don't we take `SuperiorProject` and turn it into `**Reasonable**Project`.```

`Here's an idea: why don't we take `SuperiorProject` and turn it into `**Reasonable**Project`.``

 ###  Multiple lines
 ---------------------------

You can use triple backticks (```) to format text as its own distinct block.

Check out this neat program I wrote:

```
x = 0
x = 2 + 2
what is x
```

## Links
==========================================

`[Visit GitHub!](www.github.com).`  [Visit GitHub!](www.github.com).

 ![Beautiful](./5.jpg)
 
 ![GIt Merge](./git merge.gif)

## Tables
==========================================

```
| Left-Aligned  | Center Aligned  | Right Aligned |
| :------------ |:---------------:| -----:|
| col 3 is      | ~~Display the~~ help window | $1600 |
| col 2 is      | centered        |   $12 |
| zebra stripes | _Closes_ a window      |    $1 |
```

| Left-Aligned  | Center Aligned  | Right Aligned |
| :------------ |:---------------:| -----:|
| col 3 is      | ~~Display the~~ help window | $1600 |
| col 2 is      | centered        |   $12 |
| zebra stripes | _Closes_ a window      |    $1 |


## Task lists
==========================================

```
- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> are supported
- [x] list syntax is required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item
```

- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> are supported
- [x] list syntax is required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item

```
- [ ] a bigger project
  - [ ] first subtask #1234
  - [ ] follow up subtask #4321
  - [ ] final subtask cc @mention
- [ ] a separate task
```
- [ ] a bigger project
  - [ ] first subtask #1234
  - [ ] follow up subtask #4321
  - [ ] final subtask cc @mention
- [ ] a separate task


## [Emoji](http://www.emoji-cheat-sheet.com/)
==========================================

:-1: `:-1:` 

:+1: `:+1:` 

:100: `:100:`

:tada: `:tada: `

:fireworks: `:fireworks:`



