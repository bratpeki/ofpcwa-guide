# Style Guidelines

> **Note**
>
> This doc is *ENTIRELY* susceptible to change!
> Please comment on it if anything is off.

## General

- Lines shouldn't cross 100 characters unless they have to (tables, URLs, etc)
- When breaking a line, don't break a word. Instead, move it into the next row

## Tables

The tables should be justified for each column up until the last.
The last column can, but doesn't have to be justified.

This ensures readability in text format.
Not making the last column justified saves on characters where
the trade-off of readabilty to size doesn't matter as much.

Given how the length of the column may change, use only one dash for the separation
between the table header and entires.

Example:

```
| Thing                 | Description |
| -                     | - |
| This is one entry     | This is one description |
| This is another entry | This is another description |
```
