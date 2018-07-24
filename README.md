# Y2 2018 Summer, Day 2: CSS Labs

## Lab 1
Before we begin, make sure to fork and clone this repository as we did yesterday:

  - Click the *Fork* button at the top right of the screen to make your own copy of the repository
  - Clone it as we did before:
  ```
  cd ~/Desktop
  git clone https://github.com/meet-projects/y2s18-css.git
  cd y2s18-css
  ```
 
1. Open hello.html and create a page with a header, two paragraphs, and at least one link.

2. Open style.css and create a style file such that the background color is blue and all text is white.

3. In your HTML file, add this somewhere inside the \<head\>:

```
<link rel="stylesheet" type="text/css" href=”style.css">
```

4. Use [coolors.co](coolors.co) to pick a better colorscheme for this website. Change the colors based on your new scheme, but do **not** use the style attribute!


### Extra

1. Learn more about color:
Read https://www.smashingmagazine.com/2010/02/color-theory-for-designer-part-3-creating-your-own-color-palettes/

2. Pick three of your favorite apps or websites, and explain which palette style they use.

3. Make another CSS file called style_alternate.css. Try your website with another colorscheme.


## Lab 2

### To get checked off, make sure you’re using a good color scheme for all the colors!

1. Use a CSS tag selector to change the color of all links.

2. Add a list of six favorite foods to your website. Use `<p>` tags to accomplish this. 

3. Use CSS class selectors to make vegetarian foods one color and non-vegetarian foods a different color.

4. Use a CSS id selector to give one element on your page a different background color.

5. Using Google and/or w3schools, find out what the following properties do. To get checked off, show each of them off on your website and explain them to your TA.
- font-family
- font-size

### Extra

- Pick one element in your page and give it a class and an ID. Then, add three CSS rules to style that element: one with a tag selector, one with a class selector, and one with an ID selector. Which one gets used? What happens if you have only two rules?
- Find or add two `<p>` and two `<a>` elements on your webpage and give all four of them the same class “muggle”. What happens if you use the selector “p.muggle”? How about “a.muggle”? Explain these selectors to your TA to get checked off.
- Add a form to your website. You should have at least three checkboxes and one radio button. Add a CSS rule that makes selected checkboxes turn blue.

## Lab 3

1. Open `lab3.html`. You will see plenty of `div`s in it, with a **title**, **sidebar** and some **content**, and a **container**.

2. Open `lab3.css`. Give the sidebar a light background color of your choosing, and make the title bar have larger letters.

3. Make the title banner have a height of 60px.

4. Position the sidebar and main content below the title, next to each other, using `position: absolute`. Have the main content be positioned 200px from the left.

5. Make it so the sidebar is exactly wide enough to touch the main content.

6. Give the container a height of 100%. This is because the container has only absolutely positioned `<div>`s inside it, which means it has zero size by default.

7. Now, give the sidebar a height of 100%.

#### Extra:
- Center the text in the title banner using the `position` and `transform` properties
- Look up the `calc()` function and how it works, and explain it to a TA
- Make the sidebar have a gradient background


## Lab 4

1. Open `lab3.css` again.

2. 