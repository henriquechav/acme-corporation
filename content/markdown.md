# Markdown

I am a paragraph in markdown with line
wrapping so fit in this width.
I am a continuation of the first paragraph
as there is no empty line before me.

I am in the second paragraph.

I am the third one. Even though there are
two line breaks before me, this does not
create any newline characters. After me there
are two spaces before the newline character.  
I have a line break before me. Even though
I am not a new paragraph, I do start on a
new line due to the manual line break via
spaces before the newline character.

# Top Level H1

## H2

#Just a tag
\# Not a heading
Also a # tag.

# Alternate H1

## Alternate H2

### H3

###### H6

- This is a list element

* This is also a list element

- This is also a list element
  - This is a sublist element
  * Also a sublist element
    - Sublist level 2
    1.  Numbered sublist
    2.  Next item
        1.  Next indent level

1. Numbered list
2. Next item
   1. Next indent level
      - Sublist non numbered

3) Back

Horizontal Lines:

---

.

---

.

---

.

---

> Na minha terra tem palmeiras onde canta o sabiá...

    Preformatted text
    mais um teste

```
Não tem diferença.
```

## Inline Formatting

_Italics_

_Italics_

**Bold**

**Bold**

**_Bold+Italics_**

this_is_not_emphasis

~~strikethrough~~

Content with a -- (dash) and a --- (long dash).

[link](http://localhost:1313/markdown)

[link](http://localhost:1313/markdown "Title on Link")

[Shared links with footnotes][target 1]

[second shared link][target 1]

[target 1]: http://footnote.com "Test"

Sample inline code `a++` can be specified here.

![Alt Text](./../image/logo.png "Optional Tooltip")

Smiley: &#x1F604;.

HTML: x<sup>2</sup>

## Tables, task lists and code blocks

| Name  | Job              |
| ----- | ---------------- |
| Alex  | Web Developer    |
| Bob   | Sys Admin        |
| Gabby | Technical Writer |

### Alternate table

| Name  | Mantra                                |
| ----- | ------------------------------------- |
| Alex  | There must be a better way.           |
| Bob   | Play it safe                          |
| Gabby | Try everything, but do what you like. |

### Table alignment

| Index | Products | Edges |
| ----: | :------- | :---: |
|    1. | Circle   |   0   |
|    2. | Line     |   1   |
|    3. | Square   |   4   |

## Acme Website task list

- [x] Get the home page up
- [x] Update Privacy Policy and Terms of Use
- [ ] Add the About page
- [ ] Start the blog
- [ ] Enable Contact Us page

## Code block

```javascript
var x = 10;
x++;
console.log(x);
```

With highlighting: :horse:

```javascript {linenos=true, linenostart=199}
while (!success) {
  tryAgain();
  attempt++;
  if (Dead) {
    break;
  }
}
```

## Direct Emojis

Smile please :smile:

I :heart: Hugo

Wink :wink:

A link to [Emojis](#direct-emojis)

## Smart conversion

This will convert to a dash --

This is followed by ellipses ...

## This is highlighted text {style="background: yellow"}

## Definition lists

Alex
: Hippy Web Developer
: Technophile

Bob
: Classic SysAdmin
: Conservative

Gabby
: Cool Contend Master
: Cautious
