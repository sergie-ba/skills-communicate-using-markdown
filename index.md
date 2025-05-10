# This is Header 1
## This is Header 2
### This is Header 3
#### This is Header 4
##### This is Header 5
###### This is Header 6

## Text formatting
This is _italic_.
This is *italic* too. 
This is **bold**.
This is __bold__ too.
***This text is both bold and italic
<ins>This text is underlined</ins>
==this text is highlighted==
~~This is a strikethrough text  ^c1ceb9

## Links
This is an external link: [Google](https://google.com)
This is a link to a note/page within the vault: [[🏠 00_Home]]
This is the same link as above but aliased: [[🏠 00_Home | Start here]]
You can link to a heading on the same page, like this [[Markdown basics#Other]]
Or you can also link to a block on the same page, like this [[Markdown basics#^c1ceb9]] ^4bc9d7
You may want to combine it with aliasing, like this [[Markdown basics#Other | Go to Other section]]

## Lists
This is an order list: 
1. Item 1
2. Item 2
3. Item 3

This list is unordered: 
- item one
	- nested item one
	- nested item two
- item two 
- item three

Task list:
- [x] item 1
- [ ] item 2
- [ ] item 3

## Other
This is a blockquote: 
> The problem with Internet quotes is that you cannot always depend on their accuracy.
> -- Abraham Lincoln

This is a nested quote:
> This is a quote
> > This is a nested quote (or Author)

This is a single line code:
`Select`
This is a chunk of code:
```sql
-- Explore the data in the table
SELECT p1.country AS country1,
	p2.country AS country2,
	p1.continent
FROM world.prime_ministers AS p1
INNER JOIN world.prime_ministers AS p2
	ON p1.continent = p2.continent
	LIMIT 10;
```

Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].

This is a footnote with a definition^[Definition of a footnote]

Or another way to use footnote is for referencing a section on a page, like this^[[[Markdown basics#Text formatting]]]. Just make sure you use triple brackets. 


[^1]: My reference.
[^2]: To add line breaks within a footnote, prefix new lines with 2 spaces.
  This is a second line.

  > [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.

<!-- This content will not appear in the rendered Markdown -->

![Image of a birch tree in a swamp](https://media.istockphoto.com/id/2177386456/uk/%D1%84%D0%BE%D1%82%D0%BE/%D0%B1%D0%B5%D1%80%D0%B5%D0%B7%D0%B0-%D0%BD%D0%B0-%D0%B1%D0%BE%D0%BB%D0%BE%D1%82%D1%96-%D0%B2-%D1%81%D0%BA%D0%B0%D0%BD%D0%B4%D0%B8%D0%BD%D0%B0%D0%B2%D1%81%D1%8C%D0%BA%D0%BE%D0%BC%D1%83-%D0%BF%D0%B5%D0%B9%D0%B7%D0%B0%D0%B6%D1%96.jpg?s=2048x2048&w=is&k=20&c=yzKN-73aMdqlp8nncsCcXI8PYL-b9I73DM-HQfUr7d4=)

```
$ git init
Initialized empty Git repository in /Users/skills/Projects/recipe-repository/.git/
```

``` javascript
var myVar = "Hello, world!";
```
