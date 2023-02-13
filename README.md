# MARKDOWN

## PARAGRAPHS, HEADERS, BLOCKQUOTES:

# A First Level Header

## A Second Level Header

Regular font: Now is the time for all good men to come to
the aid of their country. This is just a
regular paragraph.

The quick brown fox jumped over the lazy
dog's back.

### Third Level Header

> This is a blockquote.
>
> This is the second paragraph in the blockquote.

> ## This is an H2 in a blockquote

---

## PHRASE EMPHASIS:

Some of these words _are emphasized_.
Some of these words _are emphasized also_.

Use two asterisks for **strong emphasis**.
Or, if you prefer, **use two underscores instead**.

LISTS:

- Candy.
- Gum.
- Booze.

this:

- Candy.
- Gum.
- Booze.

and this:

- Candy.
- Gum.
- Booze.

ll produce the same output:

<ul>
<li>Candy.</li>
<li>Gum.</li>
<li>Booze.</li>
</ul>

Ordered (numbered) lists use regular numbers, followed by periods, as list markers:

1.  Red
2.  Green
3.  Blue

- A list item.

  With multiple paragraphs.

- Another item in the list.

---

## LINKS:

This site was built using [GitHub Pages](https://pages.github.com/).

This is an [example link](http://example.com/) without a title.

This is an [example link](http://example.com/ 'With a Title') with a title.

You can search for your new best friend at your local [SPCA][1] or find a resuce near you with [Pet Finder][2] or [Adopt A Pet][3].

[1]: https://ontariospca.ca/ 'SPCA'
[2]: https://www.petfinder.com/ 'Pet Finder'
[3]: https://www.adoptapet.com/ 'Adopt A Pet'

Use the same link in many places:

Find me on [LinkedIn][my linkedin].

If you need support, [Message me][my linkedin].

[my linkedin]: https://www.linkedin.com/in/avatorre/

---

## RELATIE LINKS:

You can define relative links and image paths in your rendered files to help readers navigate to other files in your repository.

[Contribution guidelines for this project](README2.md)

---

## IMAGES:

When you want to display an image which is in your repository, you should use relative link (Hover to see titles):

![peace](/images/Screenshot%202023-02-13%20at%2012.10.49%20PM.png 'Sometimes I have straight hair')

![wink][id]

[id]: /images/Screenshot%202023-02-13%20at%2012.11.01%20PM.png 'Sometimes I have wavey hair'

Whenyou want to use an image from the internet you should use the absolute link:

![kiss](/images/Screenshot%202023-02-13%20at%2012.28.55%20PM.png 'Sometimes I have fancy hair')

## ![me as Octocat](https://octodex.github.com/images/femalecodertocat.png)

---

## CODE:

I strongly recommend against using any `<blink>` tags.

I wish SmartyPants used named entities like `&mdash;`
instead of decimal-encoded entites like `&#8212;`.

If you want your page to validate under XHTML 1.0 Strict,
you've got to put paragraph tags in your blockquotes:

    <blockquote>
        <p>For example.</p>
    </blockquote>

```javascript
const = something;

if(yes){
  console.log(yes);
}
```

```javascript
var s = 'JavaScript syntax highlighting';
alert(s);
```

```python
s = "Python syntax highlighting"
print s
```

---

## STYLING:

**This is bold text**

_This text is italicized_

~~This was mistaken text~~

**This text is _extremely_ important**

**_All this text is important_**

Text<sup>This is a superscript text</sup>

Text <sub>This is a subscript text</sub>

---

## QUOTES:

> "Text that is a quote"

---

## COLOUR MODELS:

Markdown doesn't support color but you can inline HTML inside Markdown:

<span style="color:yellow">some _blue_ text</span>

<span style="color:teal">some _teal_ text</span>

<span style="color:purple">some _purple_ text</span>

Some Markdown text with <span style="color:blue">some _blue_ text</span>.

<span style="color:green">some **This is Green Bold.** text</span>

<span style="color:red"> _some emphasized markdown text_</span>

---

## DROPDOWNS:

<details> 
<summary>Dropdown Menu</summary>
Add the following line to your `Profile` by using syntax highlighting:

    This could be anything?

Yes, Anything

</details>

<details>
  <summary>Something Else</summary>
    Or don't, it's your call, whatever dude, no space means no code. 
</details>

---

## BADGES:

With link:

[![standard-readme compliant](https://img.shields.io/badge/standard--readme-OK-green.svg?style=flat-square)](https://github.com/RichardLitt/standard-readme)

Wihout link:

![standard-readme compliant](https://img.shields.io/badge/standard--readme-OK-green.svg?style=flat-square)

Fantastic Dev Badges:

https://home.aveek.io/GitHub-Profile-Badges/

![Jvascript](https://img.shields.io/badge/JavaScript-F7DF1E.svg?style=for-the-badge&logo=JavaScript&logoColor=black)

![CSS3](https://img.shields.io/badge/CSS3-1572B6.svg?style=for-the-badge&logo=CSS3&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB.svg?style=for-the-badge&logo=React&logoColor=black)
![Axios](https://img.shields.io/badge/Axios-5A29E4.svg?style=for-the-badge&logo=Axios&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB.svg?style=for-the-badge&logo=Python&logoColor=white)

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6.svg?style=for-the-badge&logo=TypeScript&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind%20CSS-06B6D4.svg?style=for-the-badge&logo=Tailwind-CSS&logoColor=white)

![Node.js](https://img.shields.io/badge/Node.js-339933.svg?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Nodemon](https://img.shields.io/badge/Nodemon-76D04B.svg?style=for-the-badge&logo=Nodemon&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000.svg?style=for-the-badge&logo=Express&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26.svg?style=for-the-badge&logo=HTML5&logoColor=white)

### Badge Generating:

https://badgen.net/

Badge Format:

    https://badgen.net/badge/:subject/:status/:color?icon=github

    "badgen.net" - default (static) badge generator
    "subject" - Text
    "status" - Text
    "color" - RGB / COLOR_NAME ( optional )
    "icon=github" - Options (label, list, icon, color)

Examples:

![blank with HG logo](https://badgen.net/badge/:subject/:status/:color?icon=github)

![blank with HG logo](https://badgen.net/badge/Ava%20is%20cool/azulverdosa/blue)

![combined statuses (default branch)](https://badgen.net//github/status/micromatch/micromatch)

![last commit (branch ref)](https://badgen.net//github/last-commit/micromatch/micromatch/gh-pages)

https://naereen.github.io/badges/

Badge Format:

    [![Generic badge](https://img.shields.io/badge/<SUBJECT>-<STATUS>-<COLOR>.svg)](https://shields.io/)

    <SUBJECT> - Badge Left Side
    <STATUS> - Badge Right Side
    <COLOR> - colour code

![example badge](https://img.shields.io/badge/Ask%20me-anything-7D3C98.svg)

[![My Custom Badge](https://img.shields.io/badge/Azul%20Verdosa-Go-1abc9c.svg)](https://shields.io/)

Shields format

https://hustakin.github.io/bestpractice/adding-beautiful-badges-into-the-markdown/

Badge Format:

    [<img src="https://img.shields.io/badge/LABEL-MESSAGE-COLOR.svg?logo=LOGO">](<LINK>)
