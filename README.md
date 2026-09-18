# BackroomFind Property Rentals

## Student Details

- Name: Lerato Mulambo
- Student Number: ST10546650
- Module: WEBDE5020
- Assessment: Portfolio of Evidence (POE) Part 2

---

# Project Overview

BackroomFind is a property rental website designed to help tenants find affordable long-term backroom accommodation in South Africa. The website connects tenants directly with landlords and provides property information, enquiry forms, and contact options.

---

# Website Pages

The website consists of the following pages:

- Home (index.html)
- About (about.html)
- Services (services.html)
- Gallery (gallery.html)
- Enquiry (enquiry.html)
- Contact (contact.html)

---

# Technologies Used

- HTML5
- CSS3
- Visual Studio Code
- GitHub

---

# CSS Styling for Desktop Solution

## 2.1 External Stylesheet

An external stylesheet named `styles.css` was created and linked to all HTML pages to ensure a consistent appearance across the website.

Features:

- Single stylesheet used on all pages
- Easy maintenance
- Consistent design

---

## 2.2 Base Style

The following default styles were applied:

- Font family
- Font size
- Text colour
- Background colour
- Margin and padding reset
- Box-sizing reset

Example:

```css
*{
    margin:0;
    padding:0;
  * box-sizing:border-box;
}

body{
 *  font-family:Arial, sans-serif;
 *  background-color:#F5F5F5;
    co*or:#333333;
}
```

---

## 2.3 Typ*graphy Styles

Typography styling *ncludes:

- Font family
- Font siz*
- Font weight
- Line height
- Let*er spacing

Example:

```css
h1{
 *  font-size:2.5rem;
    font-weigh*:700;
}

p{
    line-height:1.6;
}*```

---

## 2.4 Layout Structure
*Flexbox and CSS Grid were used to *reate page layouts.

Structure inc*udes:

- Header
- Navigation
- Mai* Content
- Footer

Example:

```cs*
nav{
    display:flex;
    justif*-content:center;
    align-items:c*nter;
}
```

---

## 2.5 Visual St*les

Visual styling includes:

- C*lours
- Background colours
- Borde*s
- Border radius
- Box shadows

E*ample:

```css
.content-card{
    *ackground-color:#ffffff;
    borde*:1px solid #dddddd;
    box-shadow*0 4px 8px rgba(0,0,0,0.1);
}
```

*--

## Interactive Effects

Pseudo*classes were used to improve usabi*ity.

```css
a:hover{
    color:#2*D366;
}

a:focus{
    outline:2px *olid #25D366;
}

a:active{
    col*r:gray;
}
```

---

# Responsive D*sign

## 3.1 Breakpoints

The webs*te was designed for:

### Desktop
*- Multi-column layout
- Full*navigation menu

### Tablet

- Adj*sted content spacing
- Responsive *avigation

### Mobile

- Single-co*umn layout
- Stacked navigation me*u

Example:

```css
@media (max-wi*th:768px){
    nav{
        flex-d*rection:column;
    }
}
```

---

*# 3.2 Relative Units

The followin* relative units were used:

- rem
* em
- %

Example:

```css
h1{
    *ont-size:2rem;
}

.container{
*   width:90%;
}
```

---

## 3.3 R*sponsive Images

Images were made *esponsive using:

```css
img{
    *ax-width:100%;
    height:auto;
}
*``

This ensures images display co*rectly on desktops, tablets, and m*bile devices.

---

## 3.4 Testing*and Iteration

The website was tes*ed using browser developer tools.
*Testing included:

- Desktop view
* Tablet view
- Mobile view

Adjust*ents were made to:

- Layout
- Nav*gation
- Typography
- Images
- Con*ent spacing

---

# Screenshots

#* Desktop View

Add your desktop sc*eenshot here.

images/desktop.png
*---

## Tablet View

Add your tabl*t screenshot here.

images/tablet.*ng

---

## Mobile View

Add your *obile screenshot here.

images/mob*le.png

---

# Changelog

## Part * Updates

- Created external style*heet
- Applied base styling
- Adde* typography styling
- Implemented *lexbox layouts
- Implemented CSS G*id layouts
- Added colour scheme
-*Added hover, focus, and active eff*cts
- Added responsive media queri*s
- Optimised responsive images
- *pdated website layout based on fee*back

---

# Challenges and Soluti*ns

## Challenge 1

Responsive lay*ut issues on smaller screens.

###*Solution

Implemented media querie* and responsive layouts.

---

## *hallenge 2

Navigation alignment p*oblems.

### Solution

Used Flexbo* to align and organise navigation *inks.

---

## Challenge 3

Image *esizing issues.

### Solution

Use* responsive image styling with max*width and height auto.

---

# Fut*re Improvements

- Add user login *unctionality
- Add search filters
* Integrate maps
- Add online booki*g features
- Improve accessibility*
---

# GitHub Repository

Reposit*ry Link:

https://github.com/LeratoMulambo-ST10546650/backroomfind

---

# Refer*nces

Adobe. (2024). Color Wheel a*d Color Theory. Available at: http*://color.adobe.com

Google Fonts. *2024). Poppins Font Family. Availa*le at: https://fonts.google.com

M*N Web Docs. (2024). HTML: HyperTex* Markup Language. Available at: ht*ps://developer.mozilla.org

MDN We* Docs. (2024). CSS: Cascading Styl* Sheets. Available at: https://dev*loper.mozilla.org

Netlify. (2024)* Netlify Documentation. Available *t: https://www.netlify.com

Nielse* Norman Group. (2024). Mobile-Firs* Design Basics. Available at: http*://www.nngroup.com

WhatsApp Busin*ss. (2024). WhatsApp Business Plat*orm. Available at: https://busines*.whatsapp.com
