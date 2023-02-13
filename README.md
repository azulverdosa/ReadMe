# MARKDOWN

## HEADERS

# A First Level Header

## A Second Level Header

### Third Level Header

#### Fourth Level Header (also normal paragraph size)

##### Fifth LEvel Header

###### Sixth Level Header

---

## LISTS

### Bulleted List

- Candy
- Gum
- Booze

  - Sublists

    - Sub-sublists
    - A list item.

      With multiple paragraphs.

  - Another item in the sublist.
    > With blockquote

### Numbered List

1.  Red
2.  Green
3.  Blue
    - Something else
      - Even something else

### Check List

- [x] Finish my changes
- [ ] Push my commits to GitHub
- [ ] Open a pull request
  - [ ] Open a pull request (again)
    - [ ] Open another pull request

### Code Block Lists

1.  Open the file.
2.  Find the following code block on line 21:

        <html>
          <head>
            <title>Test</title>
          </head>

3.  Update the title to match the name of your website.

### Images In A List

1. Open the file containing the photo of me.
2. Marvel at its beauty.

   ![Tux, the Linux mascot](/images/Screenshot%202023-02-13%20at%203.37.50%20PM.png)

3. Close the file.

---

## TABLES

| Left-aligned | Center-aligned | Right-aligned |
| :----------- | :------------: | ------------: |
| git status   |   git status   |    git status |
| git diff     |    git diff    |      git diff |

---

## LINKS

This site was built using [GitHub Pages](https://pages.github.com/).

    This site was built using [GitHub Pages](https://pages.github.com/).

This is an [example link](http://example.com/) without a title.

    This is an [example link](http://example.com/) without a title.

This is an [example link](http://example.com/ 'With a Title') with a title.

    This is an [example link](http://example.com/ 'With a Title') with a title.

You can search for your new best friend at your local [SPCA][1] or find a resuce near you with [Pet Finder][2] or [Adopt A Pet][3].

[1]: https://ontariospca.ca/ 'SPCA'
[2]: https://www.petfinder.com/ 'Pet Finder'
[3]: https://www.adoptapet.com/ 'Adopt A Pet'

    You can search for your new best friend at your local [SPCA][1] or find a resuce near you with [Pet Finder][2] or [Adopt A Pet][3].

    [1]: https://ontariospca.ca/ 'SPCA'
    [2]: https://www.petfinder.com/ 'Pet Finder'
    [3]: https://www.adoptapet.com/ 'Adopt A Pet'

Use the same link in many places:

Find me on [LinkedIn][my linkedin].

If you need support, [Message me][my linkedin].

[my linkedin]: https://www.linkedin.com/in/avatorre/

    Find me on [LinkedIn][my linkedin].

    If you need support, [Message me][my linkedin].

    [my linkedin]: https://www.linkedin.com/in/avatorre/

### URLs and Emails

<https://www.markdownguide.org>

<fake@example.com>

    <https://www.markdownguide.org>
    <fake@example.com>

### Link Styling

I love supporting the **[EFF](https://eff.org)**.
This is the _[Markdown Guide](https://www.markdownguide.org)_.

    I love supporting the **[EFF](https://eff.org)**.
    This is the *[Markdown Guide](https://www.markdownguide.org)*.
    See the section on [`code`](#code).

See the section on [`code`](#code).

---

## RELATIVE LINKS:

You can define relative links and image paths in your rendered files to help readers navigate to other files in your repository.

[Contribution guidelines for this project](README2.md)

---

## IMAGES:

When you want to display an image which is in your repository, you should use relative link (Hover to see titles):

    ![peace](/images/Screenshot%202023-02-13%20at%2012.10.49%20PM.png 'Sometimes I have straight hair')

![peace](/images/Screenshot%202023-02-13%20at%2012.10.49%20PM.png 'Sometimes I have straight hair')

    ![wink][id]

    [id]: /images/Screenshot%202023-02-13%20at%2012.11.01%20PM.png 'Sometimes I have wavey hair'

![wink][id]

[id]: /images/Screenshot%202023-02-13%20at%2012.11.01%20PM.png 'Sometimes I have wavey hair'

    ![kiss](/images/Screenshot%202023-02-13%20at%2012.28.55%20PM.png 'Sometimes I have fancy hair')

![kiss](/images/Screenshot%202023-02-13%20at%2012.28.55%20PM.png 'Sometimes I have fancy hair')

Whenyou want to use an image from the internet you should use the absolute link:

    ![me as Octocat](https://octodex.github.com/images/femalecodertocat.png)

![me as Octocat](https://octodex.github.com/images/femalecodertocat.png)

---

## CODE

I wish SmartyPants used named entities like `&mdash;`
instead of decimal-encoded entites like `&#8212;`.

Use double backticks for backticked-ed code : `` Use `code` in your Markdown file. ``

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

## STYLING

**This is bold text**

_This text is italicized_

~~This was mistaken text~~

**This text is _extremely_ important**

**_All this text is important_**

Text<sup>This is a superscript text</sup>

Text <sub>This is a subscript text</sub>

---

## HORIZONTAL RULE

Use \_\_\_ and try to put a blank line before...

---

...and after a horizontal rule.

---

## DROPDOWNS

<details> 
<summary>Dropdown Menu</summary>
This could be anything?

Yes, Anything

</details>

    <details>
    <summary>Dropdown Menu</summary>
    Add the following line to your `Profile` by using syntax highlighting:

        This could be anything?

    Yes, Anything

    </details>

<details>
  <summary>Something Else</summary>
  Another dropdown!
</details>

---

## BLOCKQUOTES

> "Text that is a quote"

### Blockquotes with Multiple Paragraphs

> Dorothy followed her through many of the beautiful rooms in her castle.
>
> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

### Nested Blockquotes

> Dorothy followed her through many of the beautiful rooms in her castle.
>
> > The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

### Blockquotes with other elements

> #### The quarterly results look great!
>
> - Revenue was off the chart.
> - Profits were higher than ever.
>
>   _Everything_ is going according to **plan**.

---

## COLOUR MODELS

Markdown doesn't support color but you can inline HTML inside Markdown:

<span style="color:yellow">some _yellow_ text:</span>

    <span style="color:yellow">some _yellow_ text</span>

<span style="color:teal">some _teal_ text:</span>

    <span style="color:teal">some _teal_ text</span>

<span style="color:purple">some _purple_ text:</span>

    <span style="color:purple">some _purple_ text</span>

Some Markdown text with <span style="color:blue">some _blue_ text</span>:

    Some Markdown text with <span style="color:blue">some _blue_ text</span>

<span style="color:green">some **This is Green Bold** text:</span>

    <span style="color:green">some **This is Green Bold** text</span>

<span style="color:red"> _some emphasized markdown text:_</span>

    span style="color:red"> _some emphasized markdown text_</span>

---

## BADGES

Fantastic Premade Dev Badges at <https://home.aveek.io/GitHub-Profile-Badges/> :

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

## BADGE GENERATING

### Fast badge generating service from <https://badgen.net/>

Badge Format:

    [![title]https://badgen.net/badge/:label/:message/:color?icon=github](<link>)

    "badgen.net/badge" - default (static) badge generator
    "label" - Left side text
    "message" - Right side text
    "color" - RGB / COLOR_NAME ( optional )
    "icon=github" - Options (label, list, icon, color)
    "<link>")

Examples:

![blank with HG logo](https://badgen.net/badge/:label/:message/:color?icon=github)

![docker star rating](https://badgen.net//docker/stars/library/mongo?icon=docker&label=stars)

[![my badge](https://badgen.net/badge/Ava%20is%20cool/azulverdosa/purple)](https://github.com/azulverdosa)

### Great examples from [Naereen](https://github.com/Naereen) on GitHub <https://naereen.github.io/badges/>:

Badge Format:

    [![Generic badge](https://img.shields.io/badge/<LABEL>-<MESSAGE>-<COLOR>.svg)](<LINK>)

    img.shields.io/badge/ - Badge generator
    <LABEL> - Left side text
    <MESSAGE> - Right side text
    <COLOR> - Colour code
    (<LINK>) - Link

Examples:

[![example badge](https://img.shields.io/badge/subject-status-7D3C98.svg)](https://shields.io/)

[![My Custom Badge](https://img.shields.io/badge/Azul%20Verdosa-Go-1abc9c.svg)](https://github.com/azulverdosa)

### Shields format from <https://shields.io/category/build>

Badge Format:

    [<img src="https://img.shields.io/badge/LABEL-MESSAGE-COLOR.svg?logo=LOGO">](<LINK>)


    img.shields.io/badge/ - Badge generator
    LABEL - Felt side tesxt
    MESSAGE - Right side text
    COLOR.svg - Colour code (optional)
    logo=LOGO - Logo
    <LINK> - link

[<img src="https://img.shields.io/badge/LABEL-MESSAGE-COLOR.svg?logo=LOGO">](LINK)

[<img src="https://img.shields.io/badge/Azul%20Verdosa-Rocks-9cf?logo=LOGO">](LINK)

## TEMPLATES

<h1 align="center"><project-name></h1>

<p align="center"><project-description></p>

## LINKS

- [Repo](https://github.com/Rohit19060/<project-name> '<project-name> Repo')

- [Live](<Homepage url> 'Live View')

- [Bugs](https://github.com/Rohit19060/<project-name>/issues 'Issues Page')

- [API](<API Link> 'API')

## Screenshots

![Home Page](/screenshots/1.png 'Home Page')

![](/screenshots/2.png)

![](/screenshots/3.png)

## Available Commands

In the project directory, you can run:

### `npm start" : "react-scripts start"`,

The app is built using `create-react-app` so this command Runs the app in Development mode. Open [http://localhost:3000](http://localhost:3000) to view it in the browser. You also need to run the server file as well to completely run the app. The page will reload if you make edits.
You will also see any lint errors in the console.

### `"npm run build": "react-scripts build"`,

Builds the app for production to the `build` folder. It correctly bundles React in production mode and optimizes the build for the best performance. The build is minified and the filenames include the hashes. Your app will be ready to deploy!

### `"npm run test": "react-scripts test"`,

Launches the test runner in the interactive watch mode.

### `"npm run dev": "concurrently "nodemon server" "npm run start"`,

For running the server and app together I am using concurrently this helps a lot in the MERN application as it runs both the server (client and server) concurrently. So you can work on them both together.

### `"serve": "node server"`

For running the server file on you can use this command.

### `npm run serve`

## Built With

- JavaScript
- Node
- NPM
- Webpack
- HTML
- CSS

## Future Updates

- [ ] Reliable Storage

## Author

**Rohit Jain**

- [Profile](https://github.com/rohit19060 'Rohit jain')
- [Email](mailto:rohitjain19060@gmail.com?subject=Hi 'Hi!')
- [Website](https://kingtechnologies.in 'Welcome')

## 🤝 Support

Contributions, issues, and feature requests are welcome!

Give a ⭐️ if you like this project!

---

1. Name, date & version -- self-explanatory names are best. collide-2d-aabb-aabb sounds promising, though it assumes I know what an , is. If the name sounds too vague or unrelated, it may be a signal to move on.

2. One-liner -- having a one-liner that describes the module is useful for getting an idea of what the module does in slightly greater detail. collide-2d-aabb-aabb says it:

   Determines whether a moving axis-aligned bounding box (AABB) collides with other AABBs.

- Awesome: it defines what an AABB is, and what the module does. Now to gauge how well it'd fit into my code:

3. Usage -- rather than starting to delve into the API docs, it'd be great to see what the module looks like in action. I can quickly determine whether the example JS fits the desired style and problem. People have lots of opinions on things like promises/callbacks and ES6. If it does fit the bill, then I can proceed to greater detail.

4. API -- the name, description, and usage of this module all sound appealing to me. I'm very likely to use this module at this point. I just need to scan the API to make sure it does exactly what I need and that it will integrate easily into my codebase. The API section ought to detail the module's objects and functions, their signatures, return types, callbacks, and events in detail. Types should be included where they aren't obvious. Caveats should be made clear.

5. Installation -- if I've read this far down, then I'm sold on trying out the module. If there are nonstandard installation notes, here's where they'd go, but even if it's just a regular npm install, I'd like to see that mentioned, too. New users start using Node all the time, so having a link to npmjs.org and an install command provides them the resources to figure out how Node modules work.

6. License -- most modules put this at the very bottom, but this might actually be better to have higher up; you're likely to exclude a module VERY quickly if it has a license incompatible with your work. I generally stick to the MIT/BSD/X11/ISC flavours. If you have a non-permissive license, stick it at the very top of the module to prevent any confusion.
