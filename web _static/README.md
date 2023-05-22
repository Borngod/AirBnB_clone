# 0x01. AirBnB clone - Web static

HTMLCSSFront-end

- By: Guillaume
- Weight: 1
- Project will start May 17, 2023 11:00 PM, must end by May 22, 2023 11:00 PM
- **Manual QA review must be done** (request it when you are done with the project)

### Concepts

_For this project, we expect you to look at these concepts:_

- [HTML/CSS](https://intranet.alxswe.com/concepts/2)
- [The trinity of front-end quality](https://intranet.alxswe.com/concepts/4)

![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2021/9/135ef103cf7ed150c9760aadc66844113dfc3d35.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20230522%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20230522T211747Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=dbaa5f5c422cb4d01ffccb14bc84007fc986da6ebcefa158a30f296516943c04)

## Background Context

### Web static, what?

Now that you have a command interpreter for managing your AirBnB objects, it’s time to make them alive!

Before developing a big and complex web application, we will build the front end step-by-step.

The first step is to “design” / “sketch” / “prototype” each element:

- Create simple HTML static pages
- Style guide
- Fake contents
- No Javascript
- No data loaded from anything

During this project, you will learn how to manipulate HTML and CSS languages. HTML is the structure of your page, it should be the first thing to write. CSS is the styling of your page, the design. I really encourage you to fix your HTML part before starting the styling. Indeed, without any structure, you can’t apply any design.

Before starting, please fork or clone the repository `AirBnB_clone` from your partner if you were not the owner of the previous project.

## Resources

**Read or watch**:

- [Learn to Code HTML & CSS](https://intranet.alxswe.com/rltoken/T9KyiA6_Tm3Ny6oTn08S-A "Learn to Code HTML & CSS") (_until “Creating Lists” included_)
- [Inline Styles in HTML](https://intranet.alxswe.com/rltoken/7NdYbImFNofpB_FXXn3otg "Inline Styles in HTML")
- [Specifics on CSS Specificity](https://intranet.alxswe.com/rltoken/z_OTPFCjmhXJJi7KJqBCbQ "Specifics on CSS Specificity")
- [CSS SpeciFishity](https://intranet.alxswe.com/rltoken/orI812cozq-yd2769VdM_w "CSS SpeciFishity")
- [Introduction to HTML](https://intranet.alxswe.com/rltoken/okP4V3RxFXHkEcQo19AnuQ "Introduction to HTML")
- [CSS](https://intranet.alxswe.com/rltoken/Ir8Ka59FO6Z_vJQ-gkSG_w "CSS")
- [MDN](https://intranet.alxswe.com/rltoken/BpSXtcWOGH0UT4XLCoQyJg "MDN")
- [center boxes](https://intranet.alxswe.com/rltoken/Tlje4XYwyZbUfHkQWGi1WQ "center boxes")

## Learning Objectives

At the end of this project, you are expected to be able to [explain to anyone](https://intranet.alxswe.com/rltoken/Zb9sTIct2xdhDCDLGF-RyQ "explain to anyone"), **without the help of Google**:

### General

- What is HTML
- How to create an HTML page
- What is a markup language
- What is the DOM
- What is an element / tag
- What is an attribute
- How does the browser load a webpage
- What is CSS
- How to add style to an element
- What is a class
- What is a selector
- How to compute CSS Specificity Value
- What are Box properties in CSS

### Copyright - Plagiarism

- You are tasked to come up with solutions for the tasks below yourself to meet with the above learning objectives.
- You will not be able to meet the objectives of this or any following project by copying and pasting someone else’s work.
- You are not allowed to publish any content of this project.
- Any form of plagiarism is strictly forbidden and will result in removal from the program.

## Requirements

### General

- Allowed editors: `vi`, `vim`, `emacs`
- All your files should end with a new line
- A `README.md` file, at the root of the folder of the project, is mandatory
- Your code should be W3C compliant and validate with [W3C-Validator](https://intranet.alxswe.com/rltoken/NzQ96QXtBTCMRDicPORzbA "W3C-Validator")
- All your CSS files should be in `styles` folder
- All your images should be in `images` folder
- You are not allowed to use `!important` and `id` (`#...` in the CSS file)
- You are not allowed to use tags `img`, `embed` and `iframe`
- You are not allowed to use Javascript
- Current screenshots have been done on `Chrome 56` or more.
- No cross browsers
- You have to follow all requirements but some `margin`/`padding` are missing - you should try to fit as much as you can to screenshots

## More Info

![](https://s3.amazonaws.com/intranet-projects-files/concepts/74/hbnb_step1.png)

### Quiz questions

**Great!** You've completed the quiz successfully! Keep going! (Show quiz)

#### Question #0

Is following CSS syntax valid?

```
body {
    color: #FF0000;
}

h3,
div.full_text
div.small_text h4
div.filters p.title {
    font-size: 20px;
}
```

- Yes
    
- No
    

#### Tips:

`,` separates multiple selector, without it’s specific selector

#### Question #1

Is the following HTML markup valid?

```
<html>
    <head>
    </head>
    <body>
        <img src="logo.png" />
    </body>
</html>
```

(elements are correctly tagged, we don’t care about `!Doctype` here)

- Yes
    
- No
    

#### Tips:

`<img />` is an empty element

#### Question #2

Is following CSS syntax valid?

```
body {
    color: #FF0000;
}
```

- Yes
    
- No
    

#### Question #3

Is following CSS syntax valid?

```
body {
    color: #FF0000;
}

h3,
div.full_text,
div.small_text h4,
div.filters p.title {
    font-size: 20px;
}
```

- Yes
    
- No
    

#### Question #4

In the following code, is the text `Best School` red?

_css:_

```
h1.title {
    color: red;
}
```

_html:_

```
<h1>Best School</h1>
```

- Yes
    
- No
    

#### Question #5

Is following CSS syntax valid?

```
body {
    color: #FF0000;
}

* {
    font-size: 14px;
}
```

- Yes
    
- No
    

#### Tips:

[Universal selectors](https://developer.mozilla.org/en-US/docs/Web/CSS/Universal_selectors "Universal selectors")

#### Question #6

Is the following HTML markup valid?

```
<html>
    <head>
    </head>
    <body>
        <h1>
            <a href="www.google.com'>Google</a>
        </h1>
    </body>
</html>
```

(elements are correctly tagged, we don’t care about `!Doctype` here)

- Yes
    
- No
    

#### Tips:

Number of quotes is important!

#### Question #7

Is the following HTML markup valid?

```
<html>
    <head>
    </head>
    <body>
        <h1>Best <b>School</h1></b>
    </body>
</html>
```

(elements are correctly tagged, we don’t care about `!Doctype` here)

- Yes
    
- No
    

#### Tips:

“Always close something before opening a new thing”

#### Question #8

In the following code, is the text `Best School` red?

_css:_

```
h1 {
    color: green;
}

span.my_title {
    color: red;
}
```

_html:_

```
<h1>
    <span class="my_title">Best School</span>
</h1>
```

- Yes
    
- No
    

#### Tips:

[CSS selector math](http://www.standardista.com/wp-content/uploads/2012/01/specificity3.pdf "CSS selector math")

#### Question #9

Is the following HTML markup valid?

```
<html>
    <head>
    </head>
    <body>
    </body>
</html>
```

(elements are correctly tagged, we don’t care about `!Doctype` here)

- Yes
    
- No
    

#### Question #10

Is following CSS syntax valid?

```
body {
    color: #FF0000;
}

div.filters h2 {
    font-size: 16px;
}
```

- Yes
    
- No
    

#### Question #11

Is the following HTML markup valid?

```
<html>
    <head>
    </head>
    <body>
    <body>
</html>
```

(elements are correctly tagged, we don’t care about `!Doctype` here)

- Yes
    
- No
    

#### Tips:

Each HTML tag must be closed

#### Question #12

In the following code, is the text `Best School` red?

_css:_

```
h1 .my_title {
    color: green;
}

.my_title {
    color: red;
}
```

_html:_

```
<h1>
    <span class="my_title">Best School</span>
</h1>
```

- Yes
    
- No
    

#### Tips:

[CSS selector math](http://www.standardista.com/wp-content/uploads/2012/01/specificity3.pdf "CSS selector math")

#### Question #13

In the following code, is the text `Best School` red?

_css:_

```
h1 div.title {
    color: red;
}
```

_html:_

```
<h1>Best School</h1>
```

- Yes
    
- No
    

#### Question #14

Is the following HTML markup valid?

```
<html></html>
```

(elements are correctly tagged, we don’t care about `!Doctype` here)

- Yes
    
- No
    

#### Question #15

Is following CSS syntax valid?

```
body {
    color: #FF0000;
}

* {
    font-size: 14px;
    text-align: center;
    margin: 30px 12px 4px;
}
```

- Yes
    
- No
    

#### Tips:

`margin` and `padding` support 4 different syntaxes: [margin](https://developer.mozilla.org/en-US/docs/Web/CSS/margin "margin")

#### Question #16

Is the following HTML markup valid?

```
<html>
    <head>
    </head>
    <body>
        <h1>
            <a href="www.google.com">Go to <b>Google</b>
        </h1>
    </body>
</html>
```

(elements are correctly tagged, we don’t care about `!Doctype` here)

- Yes
    
- No
    

#### Question #17

Is following CSS syntax valid?

```
body {
    color: #FF0000;
}

* {
    font-size: 14px;
    font-weight: 400
    text-align: center;
}
```

- Yes
    
- No
    

#### Tips:

Betty for CSS!

#### Question #18

Is following CSS syntax valid?

```
body {
    color: #FF0000;
}

div.filters p.title h2 span.text.big {
    font-size: 20px;
}
```

- Yes
    
- No
    

#### Question #19

Is following CSS syntax valid?

```
body {
    color: #FF0000;
}

* {
    font-size: 14px;
    text-align: center;

    h1 {
        margin: 30px;
    }
}
```

- Yes
    
- No
    

#### Tips:

CSS vs SCSS

#### Question #20

In the following code, is the text `Best School` red?

_css:_

```
h3 span.text,
h1,
div.title {
    color: red;
}
```

_html:_

```
<h1>Best School</h1>
```

- Yes
    
- No
    

#### Question #21

Is following CSS syntax valid?

```
body {
    color: #FF0000;
}

h1.title {
    font-size: 16px;
}
```

- Yes
    
- No
    

#### Question #22

In the following code, is the text `Best School` red?

_css:_

```
h1 {
    color: red;
}
```

_html:_

```
<h1>Best School</h1>
```

- Yes
    
- No
    

#### Question #23

In the following code, is the text `Best School` red?

_css:_

```
h2 {
    color: red;
}
```

_html:_

```
<h1>Best School</h1>
```

- Yes
    
- No
    

## Tasks

### 0\. Inline styling

mandatory

Write an HTML page that displays a header and a footer.

Layout:

- Body:
    - no margin
    - no padding
- Header:
    - color #FF0000 (red)
    - height: 70px
    - width: 100%
- Footer:
    - color #00FF00 (green)
    - height: 60px
    - width: 100%
    - text `Best School` center vertically and horizontally
    - always at the bottom at the page

Requirements:

- You must use the `header` and `footer` tags
- You are not allowed to import any files
- You are not allowed to use the `style` tag in the `head` tag
- Use inline styling for all your tags

![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2021/12/98f4ac1b0644512ce7ae91a9e8e61e8fe174911d.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20230522%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20230522T211747Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=244c15e9a0c4bb16baaa243e2b16c6ee4a86e1305be75090106c178057119cc4)

**Repo:**

- GitHub repository: `AirBnB_clone`
- Directory: `web_static`
- File: `0-index.html`

Done?! Help

×

#### Students who are done with "0. Inline styling"

### 1\. Head styling

mandatory

Write an HTML page that displays a header and a footer by using the `style` tag in the `head` tag (same as `0-index.html`)

Requirements:

- You must use the `header` and `footer` tags
- You are not allowed to import any files
- No inline styling
- You must use the `style` tag in the `head` tag

The layout must be exactly the same as `0-index.html`

**Repo:**

- GitHub repository: `AirBnB_clone`
- Directory: `web_static`
- File: `1-index.html`

Done?! Help

×

#### Students who are done with "1. Head styling"

### 2\. CSS files

mandatory

Write an HTML page that displays a header and a footer by using CSS files (same as `1-index.html`)

Requirements:

- You must use the `header` and `footer` tags
- No inline styling
- You must have 3 CSS files:
    - `styles/2-common.css`: for global style (i.e. the `body` style)
    - `styles/2-header.css`: for header style
    - `styles/2-footer.css`: for footer style

The layout must be exactly the same as `1-index.html`

**Repo:**

- GitHub repository: `AirBnB_clone`
- Directory: `web_static`
- File: `2-index.html, styles/2-common.css, styles/2-header.css, styles/2-footer.css`

Done?! Help

×

#### Students who are done with "2. CSS files"

### 3\. Zoning done!

mandatory

Write an HTML page that displays a header and footer by using CSS files (same as `2-index.html`)

Layout:

- Common:
    - no margin
    - no padding
    - font color: #484848
    - font size: 14px
    - font family: `Circular,"Helvetica Neue",Helvetica,Arial,sans-serif;`
    - [icon](https://s3.amazonaws.com/intranet-projects-files/holbertonschool-higher-level_programming+/268/icon.png "icon") in the browser tab
- Header:
    - color: white
    - height: 70px
    - width: 100%
    - border bottom 1px #CCCCCC
    - [logo](https://s3.amazonaws.com/intranet-projects-files/holbertonschool-higher-level_programming+/268/logo.png "logo") align on left and center vertically (20px space at the left)
- Footer:
    - color white
    - height: 60px
    - width: 100%
    - border top 1px #CCCCCC
    - text `Best School` center vertically and horizontally
    - always at the bottom at the page

Requirements:

- No inline style
- You are not allowed to use the `img` tag
- You are not allowed to use the `style` tag in the `head` tag
- All images must be stored in the `images` folder
- You must have 3 CSS files:
    - `styles/3-common.css`: for the global style (i.e `body` style)
    - `styles/3-header.css`: for the header style
    - `styles/3-footer.css`: for the footer style

![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2021/12/2be1eda05a0d9097c210f2d3482a59aa858c5711.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20230522%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20230522T211747Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=71ea6b736f0a3a4216a780690344dcae6c246e6910e825e17363b9d5b9855dc4)

**Repo:**

- GitHub repository: `AirBnB_clone`
- Directory: `web_static`
- File: `3-index.html, styles/3-common.css, styles/3-header.css, styles/3-footer.css, images/`

Done?! Help

×

#### Students who are done with "3. Zoning done!"

### 4\. Search!

mandatory

Write an HTML page that displays a header, footer and a filters box with a search button.

Layout: (based on `3-index.html`)

- Container:
    - between `header` and `footer` tags, add a `div`:
        - classname: `container`
        - max width 1000px
        - margin top and bottom 30px - it should be 30px under the bottom of the `header` (screenshot)
        - center horizontally
- Filter section:
    - tag `section`
    - classname `filters`
    - inside the `.container`
    - color white
    - height: 70px
    - width: 100% of the container
    - border 1px #DDDDDD with radius 4px
- Button search:
    - tag `button`
    - text `Search`
    - font size: 18px
    - inside the section filters
    - background color #FF5A5F
    - text color #FFFFFF
    - height: 48px
    - width: 20% of the section filters
    - no borders
    - border radius: 4px
    - center vertically and at 30px of the right border
    - change opacity to 90% when the mouse is on the button

Requirements:

- You must use: `header`, `footer`, `section`, `button` tags
- No inline style
- You are not allowed to use the `img` tag
- You are not allowed to use the `style` tag in the `head` tag
- All images must be stored in the `images` folder
- You must have 4 CSS files:
    - `styles/4-common.css`: for the global style (`body` and `.container` styles)
    - `styles/3-header.css`: for the header style
    - `styles/3-footer.css`: for the footer style
    - `styles/4-filters.css`: for the filters style
- `4-index.html` **won’t be W3C valid**, don’t worry, it’s temporary

![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2021/12/f959154b0cdf1cdf71ddef04e3787ef28462793e.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20230522%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20230522T211747Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=148e98700f44cbf087f2be59636e2e83674ffec73158669708adff0dc042e6b4)

**Repo:**

- GitHub repository: `AirBnB_clone`
- Directory: `web_static`
- File: `4-index.html, styles/4-common.css, styles/3-header.css, styles/3-footer.css, styles/4-filters.css, images/`

Done?! Help

×

#### Students who are done with "4. Search!"

### 5\. More filters

mandatory

Write an HTML page that displays a header, footer and a filters box.

Layout: (based on `4-index.html`)

- Locations and Amenities filters:
    - tag: `div`
    - classname: `locations` for location tag and `amenities` for the other
    - inside the section filters (same level as the `button` Search)
    - height: 100% of the section filters
    - width: 25% of the section filters
    - border right #DDDDDD 1px only for the first left filter
    - contains a title:
        - tag: `h3`
        - font weight: 600  
            
        - text `States` or `Amenities`
    - contains a subtitle:
        - tag: `h4`
        - font weight: 400  
            
        - font size: 14px
        - text with fake contents

Requirements:

- You must use: `header`, `footer`, `section`, `button`, `h3`, `h4` tags
- No inline style
- You are not allowed to use the `img` tag
- You are not allowed to use the `style` tag in the `head` tag
- All images must be stored in the `images` folder
- You must have 4 CSS files:
    - `styles/4-common.css`: for the global style (`body` and `.container` styles)
    - `styles/3-header.css`: for the header style
    - `styles/3-footer.css`: for the footer style
    - `styles/5-filters.css`: for the filters style

![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2021/12/85bfa50b96c2985723daa75b5e22f75ef16e2b2e.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20230522%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20230522T211747Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=354d58b3060fc5692f8a460f3453144ef5408325072901fc5b87e3613302b1d0)

**Repo:**

- GitHub repository: `AirBnB_clone`
- Directory: `web_static`
- File: `5-index.html, styles/4-common.css, styles/3-header.css, styles/3-footer.css, styles/5-filters.css, images/`

Done?! Help

×

#### Students who are done with "5. More filters"

### 6\. It's (h)over

mandatory

Write an HTML page that displays a header, footer and a filters box with dropdown.

Layout: (based on `5-index.html`)

- Update Locations and Amenities filters to display a contextual dropdown when the mouse is on the filter `div`:
    - tag `ul`
    - classname `popover`
    - text should be fake now
    - inside each `div`
    - not displayed by default
    - color #FAFAFA
    - width same as the `div` filter
    - border #DDDDDD 1px with border radius 4px
    - no list display
    - Location filter has 2 levels of `ul`/`li`:
        - state -> cities
        - state name must be display in a `h2` tag (font size 16px)

Requirements:

- You must use: `header`, `footer`, `section`, `button`, `h3`, `h4`, `ul`, `li` tags
- No inline style
- You are not allowed to use the `img` tag
- You are not allowed to use the `style` tag in the `head` tag
- All images must be stored in the `images` folder
- You must have 4 CSS files:
    - `styles/4-common.css`: for the global style (`body` and `.container` styles)
    - `styles/3-header.css`: for the header style
    - `styles/3-footer.css`: for the footer style
    - `styles/6-filters.css`: for the filters style

![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2021/12/6262f13624dca23ca19db505c44f88faddb82ebb.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20230522%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20230522T211747Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=d3f1799abfe8873ca24b1599acc38433df08ceeaaa18c456181060e9e72a8a09) ![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2021/12/6e6bdfa13fa88a5f439d9e2b1dade826dd95529b.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20230522%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20230522T211747Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=1a32a9f3fdfc9f187540fa390041fa5be60e1096d712468fb10227c94cd978cd)

**Repo:**

- GitHub repository: `AirBnB_clone`
- Directory: `web_static`
- File: `6-index.html, styles/4-common.css, styles/3-header.css, styles/3-footer.css, styles/6-filters.css, images/`

Done?! Help

×

#### Students who are done with "6. It's (h)over"

### 7\. Display results

mandatory

Write an HTML page that displays a header, footer, a filters box with dropdown and results.

Layout: (based on `6-index.html`)

- Add Places section:
    - tag: `section`
    - classname: `places`
    - same level as the filters section, inside `.container`
    - contains a title:
        - tag: `h1`
        - text: `Places`
        - align in the top left
        - font size: 30px
    - contains multiple “Places” as listing (horizontal or vertical) describe by:
        - tag: `article`
        - width: 390px
        - padding and margin 20px
        - border #FF5A5F 1px with radius 4px
        - contains the place name:
            - tag: `h2`
            - font size: 30px
            - center horizontally

Requirements:

- You must use: `header`, `footer`, `section`, `article`, `button`, `h1`, `h2`, `h3`, `h4`, `ul`, `li` tags
- No inline style
- You are not allowed to use the `img` tag
- You are not allowed to use the `style` tag in the `head` tag
- All images must be stored in the `images` folder
- You must have 5 CSS files:
    - `styles/4-common.css`: for the global style (i.e. `body` and `.container` styles)
    - `styles/3-header.css`: for the header style
    - `styles/3-footer.css`: for footer style
    - `styles/6-filters.css`: for the filters style
    - `styles/7-places.css`: for the places style

![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2021/12/bca4d17fbe21a58b66a9d5d6b85df4801d147dd0.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20230522%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20230522T211747Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=80e15aebe33957ec24247d98f9cabdaae68cea484413c195df9af5a761501b38)

**Repo:**

- GitHub repository: `AirBnB_clone`
- Directory: `web_static`
- File: `7-index.html, styles/4-common.css, styles/3-header.css, styles/3-footer.css, styles/6-filters.css, styles/7-places.css, images/`

Done?! Help

×

#### Students who are done with "7. Display results"

### 8\. More details

mandatory

Write an HTML page that displays a header, a footer, a filter box (dropdown list) and the result of the search.

Layout: (based on `7-index.html`)

Add more information to a Place `article`:

- Price by night:
    - tag: `div`
    - classname: `price_by_night`
    - same level as the place name
    - font color: #FF5A5F
    - border: #FF5A5F 4px rounded
    - min width: 60px
    - height: 60px
    - font size: 30px
    - align: the top right (with space)
- Information section:
    - tag: `div`
    - classname: `information`
    - height: 80px
    - border: top and bottom #DDDDDD 1px
    - contains (align vertically):
        - Number of guests:
            - tag: `div`
            - classname: `max_guest`
            - width: 100px
            - fake text
            - [icon](https://s3.amazonaws.com/intranet-projects-files/holbertonschool-higher-level_programming+/268/icon_group.png "icon")
        - Number of bedrooms:
            - tag: `div`
            - classname: `number_rooms`
            - width: 100px
            - fake text
            - [icon](https://s3.amazonaws.com/intranet-projects-files/holbertonschool-higher-level_programming+/268/icon_bed.png "icon")
        - Number of bathrooms:
            - tag: `div`
            - classname: `number_bathrooms`
            - width: 100px
            - fake text
            - [icon](https://s3.amazonaws.com/intranet-projects-files/holbertonschool-higher-level_programming+/268/icon_bath.png "icon")
- User section:
    - tag: `div`
    - classname: `user`
    - text `Owner: <fake text>`
    - `Owner` text should be in bold
- Description section:
    - tag: `div`
    - classname: `description`

Requirements:

- You must use: `header`, `footer`, `section`, `article`, `button`, `h1`, `h2`, `h3`, `h4`, `ul`, `li` tags
- No inline style
- You are not allowed to use the `img` tag
- You are not allowed to use the `style` tag in the `head` tag
- All images must be stored in the `images` folder
- You must have 5 CSS files:
    - `styles/4-common.css`: for the global style (i.e. `body` and `.container` styles)
    - `styles/3-header.css`: for the header style
    - `styles/3-footer.css`: for the footer style
    - `styles/6-filters.css`: for the filters style
    - `styles/8-places.css`: for the places style

![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2021/12/f4b2d4ef94bd3a2e7e1ddefa81236595686d270e.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20230522%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20230522T211747Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=076c630c29f20a02591a1218b1373267a120b32d9733aaa19721b47af3f6a7ad)

**Repo:**

- GitHub repository: `AirBnB_clone`
- Directory: `web_static`
- File: `8-index.html, styles/4-common.css, styles/3-header.css, styles/3-footer.css, styles/6-filters.css, styles/8-places.css, images/`

