Progress for Learn typography
Step 21
Give your h1 element a class attribute set to bold. This will make the text bold again.
Step 22
Horizontal spacing between equally important elements can increase the readability of your text.
Wrap the text 2/3 cup (55g) in a span element.
Step 23
Now we can add the horizontal spacing using flex. In your p selector, add a display property set to flex and a justify-content property set to space-between.
Step 24
Wrap everything within the .label element in a new header element.
Step 25
Now update your h1 selector to be header h1 to specifically target your h1 element within your new header.
Step 26
Create a new div element below your header element, and give it a class attribute set to divider large.
Step 27
Create a new .large selector and give it a height property set to 10px. Also create an .large, .medium selector and set the background-color property to black.
Step 28
You may notice there is still a small border at the bottom of your .large element. To reset this, give your .large, .medium selector a border property set to 0.
Note: the medium(medium) class will be utilized later for the thinner bars of the nutrition label.
Step 29Passed
Create a new div below your .large element and give it a class attribute set to calories-info.
Step 30Passed
Within your .calories-info element, create a div element. Give that div element a class attribute set to left-container. Within the newly created div element, create a h2 element with the text Amount per serving. Give the h2 element a class attribute set to bold small-text.
Step 31Passed
The rem unit stands for root em, and is relative to the font size of the html element.
Create a .small-text selector and set the font-size to 0.85rem, which would calculate to roughly 13.6px (remember that you set your html to have a font-size of 16px).
Step 32
Create a .calories-info h2 selector and remove all margins.
Step 33
Below your .small-text element, create a new p element with the text Calories. Also below the .left-container element, create a new span element with the text 230.
Step 34
Create a new .calories-info selector and give it a display property set to flex. Also give it a justify-content property set to space-between and align-items property set to flex-end.
Step 35
Create a new .left-container p selector setting the top and bottom margin to -5px, and the left and right margin to -2px. Also set the font-size to 2em and font-weight to 700.
Step 36
Create a .calories-info span selector, set its font-size to 2.4em and font-weight to 700.
Typography is often more art than science. You may have to tweak things like alignment until it looks correct.
Give your .calories-info span selector a margin set to -7px -2px. This will shift your 230 text into place.
Step 37Passed
Typography is often more art than science. You may have to tweak things like alignment until it looks correct.
Give your .calories-info span selector a margin set to -7px -2px. This will shift your 230 text into place.
Step 38Passed
Below your .calories-info element, add a div with the class attribute set to divider medium.
Step 39
Create an .medium selector and give it a height property of 5px.
Step 40
Create a new div element below your .medium element. Give it a class attribute set to daily-value small-text. Within this new div, add a p element with the text % Daily Value *, and set the class attribute to bold right.
Step 41
The text % Daily Value * should be aligned to the right. Create a .right selector and use the justify-content property to do it.
Step 42
Use your existing .divider element as an example to add a new divider after the p element.
Step 43
After your last .divider element, create a p element and give it the text Total Fat 8g 10%. Wrap the text Total Fat in a span element with the class of bold. Wrap the text 10% in another span element with the class of bold. Finally, nest the Total Fat span element and the text 8g in an additional span element for alignment.
Step 44Passed
Below your element with the Total Fat text, create a new p element with the text Saturated Fat 1g 5%. Wrap the 5% in a span with the class attribute set to bold. In this case this is enough to align the percentage to 5%.
Step 45
This new p element will need to be indented. Give it a class set to indent.
Step 46
Create a new .indent selector and give it a margin-left property set to 1em.
Step 47
Create a .daily-value p selector to target all of your p elements in the daily-value section. Give this new selector a border-bottom set to 1px solid #888989.
Step 48Passed
The bottom borders under your % Daily Value * and Saturated Fat 1g 5% elements do not extend the full width of the label. Add no-divider to the class for these two elements.
Step 49Passed
The :not pseudo-selector can be used to select all elements that do not match the given CSS rule.

div:not(#example) {
  color: red;
}
The above selects all div elements without an id of example.

Modify your .daily-value p selector to exclude the .no-divider elements.
Step 50
Now you will have to add separate dividers below your .no-divider elements.

Your first .no-divider element has a .divider after it. Create another .divider after your second .no-divider element.
Step 51
After your last .divider, create another p element with the text Trans Fat 0g. Italicize the word Trans by wrapping it in an i element. Give the new p element the class attribute set to indent no-divider. Wrap Trans Fat 0g in a span element for alignment.
Step 52
Create another .divider after your last p element.
Step 53
After your last .divider, create a new p element with the text Cholesterol 0mg 0%. Wrap the text Cholesterol in a span element, and give that span element the class of bold. Wrap the text 0% in another span element, with the class of bold. Finally, nest the Cholesterol span element and the text 0mg in an additional span element for alignment.
Step 54
Below your last p element, create another p element with the text Sodium 160mg 7%. Wrap the text Sodium in a span element with a class attribute set to bold. Wrap the 7% text in another span element with the class set to bold. Also add an additional span element around Sodium 160mg for aligning it correctly.
Step 55
Below your last p element, add another p element with the text Total Carbohydrate 37g 13%. Like before, use span elements to make the text Total Carbohydrate and 13% bold. Also add an additional span element around the Total Carbohydrate 37g text to have it aligned to the left and 13% to the right.
Step 56
Below your last p element, add another p element with the text Dietary Fiber 4g. Give the p element the class necessary to indent it and remove the dividing border. Then create a divider below that p element.
Step 57Passed
Create another p element after your last .divider, and give it the text Total Sugars 12g. Assign that p element the class values necessary to indent it and remove the bottom border. Then create another .divider below your new p element.
Step 58
The advantage to creating these dividers is that you can apply specific classes to style them individually. Add double-indent to the class for your last .divider.
Step 59
Create a .double-indent selector and give it a left margin of 2em.
Step 60
Below your .double-indent element, add a new p element with the text Includes 10g Added Sugars 20%. Your new p element should also be double indented, and have no bottom border. Use a span to make the 20% bold and right aligned.

Then create another divider after that p element.
Step 61
After your last divider, create another p element with the text Protein 3g. Use the necessary classes to remove the bottom border, and a span to make the Protein bold.

Following this element, create a large divider.
Step 62
Create another p element below your large divider. Give the p element the text Vitamin D 2mcg 10%.

The p element contains only text, you can wrap the percentage in a span element so that it is considered a separate entity from the rest of the text, and it's moved to the right.
Step 63
Create another p element, give it the text Calcium 260mg 20%. Align 20% to the right. Below that, create a p element with the text Iron 8mg 45%, aligning the 45% to the right.
Step 64
Create the final p element for your .daily-value section. Give it the text Potassium 235mg 6%. Align the 6% text to the right, and remove the bottom border of the p element.
Step 65
Add a medium divider after your .daily-value element. Below that new divider, create a p element with the class attribute set to note.

Give the p element the following text:
Step 66
Create a .note selector, and set the size of the font to 0.6rem. Also set the top and bottom margins to 5px, removing the left and right margins.
Step 67
Give the .note selector a left and right padding of 8px, removing the top and bottom padding. Also set the text-indent property to -8px.

With these last changes, your nutrition label is complete!