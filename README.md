# Y2 2018 Summer, Day 2: CSS Labs

## Lab 1
Before we begin, make sure to clone this repository as we did yesterday:

```
cd ~/Desktop
git clone https://github.com/meet-projects/y2s18-css.git
cd y2s18-css
subl hello.html
```
1. Open hello.html and create a page with a header, two paragraphs, and at least one link. If your partner wasn’t here yesterday, teach them about the `<p>`, `<h3>`, and `<a>` tags.

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

1. Open `lab3.html`. You will see plenty of `div`s in it, with content, but no classes or ids!

2. Your job is to add classes and ids until the page has a *title*, a *side bar*, *side bar links*, and a *main content* section.

3. Open `lab3.css`. Give the sidebar a light background color of your choosing, and make the title bar have larger letters.

4. Make it so that the side bar is to the left of the main content (using the `float` attribute). Then, make the sidebar take up 10% of the width of the screen, and the main content 90%.

5. Have the title banner take up 10% of the height of the screen, using the `height` attribute, and the side bar 90%.

#### Extra:
- Center the text in the title banner and in the sidebar contents using the `text-align` property
- Look up the `calc()` function and how it works
- Make the sidebar have a gradient background
