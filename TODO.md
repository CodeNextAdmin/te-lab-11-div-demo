# TODO 🚧

## Review structure

Begin by looking at the structure of the HTML. This is a basic example of nesting elements inside parent containers.
#### Discuss these questions:
1. What is the top-most parent container?
2. What happens to the elements as you stretch and shrink the window?
3. What is different about the div elements?

## The main container
1. Notice the main container begins with a hashtag. That is because it is an ID selector, only one can exist with this name.
```css
#main-container  {
  
  
}

```

2. Notice the other ones begin with a ``.``   This is because they are class selectors. You can have multiple ones and the CSS will affec them all.
3. Change the main container's width. Try to use both pixels and percentage. 

```css

#main-container  {
  /* will be 40% the width of the parent (the body) */
  width: 40%; 
  
}

```
4. Add a border with rounded corners.
```css

  border-style:solid;
  border-radius: 10px;
  border-color: #white;


```

5. Adjust margins and padding. How does it change? How does it affect the child elements?

## Parent divs
The  ``<div class="parent">`` has a background color, size, margins and padding too. 
1. Adjust the margins to see how it changes in relation to it's parent container. 
2. Change the width and height. Notice how adding the rule twice only applies the second rule.
3. Notice the ``display`` property that is commented out. What does it do when you activate it?

## Child divs
Each child div has one emoji as html content. 
1. Notice how you can set the font size of child elements, even though they are not wrapped in HTML tags.
2. Adjust values to see the output.
3. Shrink and stretch the window to see how your changes affect the output.

## Challenge:

1. Make this layout:
 ![Challenge Solution](https://i.imgur.com/faOVISa.png)
 
2. Make your own layout and explain how you did it. 