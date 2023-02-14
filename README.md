# NOTE:

This guy is a work in progress, but will eventually be my guide to building better READMEs for all my projects. A project for other projects 😊

---

### Table Of Contents

- [Headers](#headers)
- [Lists](#lists)
- [Tables](#tables)
- [Links](#links)
- [Relative Links](#relative-links)
- [Images](#images)
- [Code](#code)
- [Styling](#styling)
- [Horizontal Rule](#horizontal-rule)
- [Drop Downs](#dropdowns)
- [Blockquotes](#blockquotes)
- [Colour Models](#colour-models)
- [Badges](#badges)
- [Generating Badges](#generating-badges)
- [Template](#template)

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
- Chocolate

  - Sublists

    - Sublist - list
    - A list item.

      With multiple paragraphs.

  - Another item in the sublist.
    > With blockquote

### Numbered List

1.  Red
2.  Green
3.  Blue
    - Sublist for the numbered list
      - And something else

### Check List

- [x] Finish my changes
- [x] Push my commits to GitHub
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

## RELATIVE LINKS

You can define relative links and image paths in your rendered files to help readers navigate to other files in your repository.

[Contribution guidelines for this project](README2.md)

---

## IMAGES

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

## GENERATING BADGES

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

## TEMPLATE

ReadMe template from [Malgorzata Rita Ły](https://github.com/ritaly/README-cheatsheet)

---

# Project Name

> Outline a brief description of your project. Live demo here.

## Table of Contents

---

- General Info
- Technologies Used
- Features
- Screenshots
- Setup
- Usage
- Project Status
- Room for Improvement
- Acknowledgements
- Contact

## General Information

---

Provide general information about your project here.
What problem does it (intend to) solve?
What is the purpose of your project?
Why did you undertake it?

## Technologies Used

---

- Tech 1 - version 1.0

- Tech 2 - version 2.0

- Tech 3 - version 3.0

## Features

---

List the ready features here:

Awesome feature 1

- Description

Awesome feature 2

- Description

Awesome feature 3

- Description

## Screenshots

---

![Home Page](/screenshots/4.png 'Home Page')
Description of screenshot

## Setup

---

What are the project requirements/dependencies? Where are they listed? A requirements.txt or a Pipfile.lock file perhaps? Where is it located?

Proceed to describe how to install / setup one's local environment / get started with the project.

### Available Commands

In the project directory, you can run:

### `"npm start" : "react-scripts start"`,

The app is built using `create-react-app` so this command Runs the app in Development mode. Open [http://localhost:3000](http://localhost:3000) to view it in the browser. You also need to run the server file as well to completely run the app. The page will reload if you make edits.
You will also see any lint errors in the console.

### `"npm run build": "react-scripts build"`,

Builds the app for production to the `build` folder. It correctly bundles React in production mode and optimizes the build for the best performance. The build is minified and the filenames include the hashes. Your app will be ready to deploy!

### `"npm run test": "react-scripts test"`,

Launches the test runner in the interactive watch mode.

### `"npm run dev": "concurrently "nodemon server" "npm run start"`,

For running the server and app together I am using concurrently this helps a lot in the MERN application as it runs both the server (client and server) concurrently. So you can work on them both together.

## Usage

---

How does one go about using it? Provide various use cases and code examples here.

    write-your-code-here

## Project Status

---

Project is: in progress / complete / no longer being worked on. If you are no longer working on it, provide reasons why.

## Room for Improvement

---

Include areas you believe need improvement / could be improved. Also add TODOs for future development.

Room for improvement:

- Improvement to be done 1
- Improvement to be done 2

To do:

- Feature to be added 1
- Feature to be added 2

## Acknowledgements

---

Give credit here.

This project was inspired by...
This project was based on this tutorial.
Many thanks to...

##Contact

---

Created by @flynerdpl - feel free to contact me!

- [GitHub Profile](https://github.com/azulverdosa 'Ava Elise')
- [LinkedIn](https://www.linkedin.com/in/avatorre/ 'linked')
- [Website](https://kingtechnologies.in 'Welcome')

## 🤝 Support

---

Contributions, issues, and feature requests are welcome!

Give a ⭐️ if you like this project!
