# Code commentary syntax cookbook

How to comment in this file?

## Simple local comments

Simple local comments are for commenting relatively to one style block.
Make a new line and underneath start two line CSS comment.
Your thoughts goes into the first comment line.

```css
/* This is super duper
 */
.class.class:hover {
    ...
}

/* Also this is interesting
 */
.class > h1 {
    ...
}
```

## Heading section comments

To keep code clean and cozy sectioning whole code is a must.
So that's what the _Heading section comments_ are made for.

Simply ident new section with two blank lines and start three line CSS comment underneath.
Then do a heading line. The heading line must have always width to 128 col.
Text underneath is uppercased and prefixed with a pipeline character.

```css
    ...
}


/* +---------------------------------------------------------------------------------------------------------------------------
 * |  MY AWESOME NEW SECTION!
 */
#stuff {
    ...
```