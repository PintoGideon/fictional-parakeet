# Learning Design

### The Cool Parts

clip-path:

# Important Fundamentals of CSS

### Responsive Design:

The website needs to look cohesive in all screen sizes.

1. Fluid Layouts- Use % rather than px for all layout related lengths.

2. Media Queries

3. Responsive Images- Images should adapt to the current viewport.

4. Correct Units

5. Desktop first vs mobile first

### Maintable and scalable code:

1. Clean
2. Easy to Understand
3. Growth
4. Reusable
5. How to organize Files
6. How to name classes
7. How to structure HTML

### Web Performance

1. Less HTTP Requests
2. Less Code
3. Compress Code
4. Use a CSS preprocessor
5. Less Images
6. Compress Images

# Behind the scenes

How CSS is Parsed?

The Cascade is the process of combining different stylesheets
and resolving conflicts between different CSS rules and declarations when more
than one rule applies to a certain element.

- Author
- User
- Browser

The cascade resolves conflicts in this order:
Importance (Weight) > Specificity > Source Order

Inheritance passes the value for some specific properties from parents to
children- more maintainable code
Properties related to text are inherited: font-family, font-size, color etc.

# Coverting px to rem- An Effective Workflow.

Why do we use rem units?

It makes writing media queries very easier.
**_1rem= 1_ root font-size\***

```html
html{ font-size:16px } .header{ top:40px ----> 4rem }
```

# The Visual Formatting Model

Algorithm that calculates boxes and determines the layout of boxes in the render tree. In order to determine the final layout
of the page.

- Dimensions of Boxes
- Box type
- Positioning Scheme
- Stacking contexts
- Other elements in the render tree
- Viewport size

# THe Box Model

Content: Text, Images etc;
Padding: Transparent area around the content, inside of the box
Border: Goes around the padding and the content
Margin: Space between boxes;
Fill area: Area the gets filled with background color

**_Total Width_**: right border + right padding + specified width + left padding + left border

**_Total Height_**: top border + top padding + specified height + bottom padding + bottom border

# Box Types

# Positioning Schemes

- Normal Flow- Default Positional Scheme
- Floats- Element is removed from the normal flow
- Absolute Positioning- Element is removed from the normal flow. We use bottom , left, right too offset the element from it's relatively positioned container

# Stacking Contexts (Z index)

# CSS Architecture

1. Think

   - Component Driven Design- Modular building blocks that make up interfaces

   - Reusable across a project

   - Independent allowing to use them anywhere on the page

2. Build

   - Block Element Modifier

```html
.block {} .block__element{} .block__element--modifier{}
```

3. Architect
   7-1 Pattern
   7 different folders for partial Sass files and
   1 main Sass file to import all other files to a compiled CSS Stylesheet

# SASS

- SASS is a CSS preprocessor, an extension of CSS that adds power and elegance to the basic language
- SASS Source Code------> Compile CSS Code

# Features

1. Variables- For reusables values such as colors , font-sizes and spacing etch

2. Nesting- Nest Selectors inside of one another

3. Operators- For Mathematical Operations

4. Partials and Imports- To Write CSS code in different files and import them all into one

5. Mixins- Write reusable pieces of code

6. Functions- Similar to Mxings with the difference that they produce a value that can be used

7. Extends- To make different selectors inherit declarations that are common to all of them

8. Control Directives- For Writing Complex code

Codepen:  https://codepen.io/anon/pen/XQvybq


# Good Parts of this Project

```
transform: skewY(-7deg)


```




