### Introduction to CSS 
- CSS works by associating rules with HTML elements.

- A CSS rule contains two parts:
  - Selector: indicates which element the rule applies to.
  - Declaration: indicates how the element should be styled.
    - Each declaration contains a property and a value, separated by a colon. 
  - An example of a CSS rule:

    p {

      font-family: Helvetica;
      
    }

- A &lt;link&gt; element is used within the &lt;head&gt; element to reference to your CSS file.  For example:

  &lt;link href="css/styles.css" type="text/css" rel="stylesheet" /&gt;

- A Class selector is written as seen here:

  .note {}

- An ID selector is written as follows:

  #introduction {}

- Descendant selector: targets elements that sit inside of another element:

  p a {}

  This will target any &lt;a&gt; element that sits within a &lt;p&gt; element.

- How do CSS rules cascade?
  - If there are two selectors that are identical, the latter of the two will take precedence.
  - If a selector is more specific than another, it will take precedence.  For example, p b is more specific than just p.

### Color

- Foreground Color is the color of the text.  It can be expressed in 3 different ways:
  - **RGB Values**. This expresses colors in terms of how much red, green, and blue are in the color.  For example: rgb(110, 100, 80).
  - **HEX Codes**. Six-digit codes that represent the amount of red, green, and blue in a color.  They are preceded by a #. For example: #42f1f4.
  - **Color Names**. There are 147 predefined color names that you can use.  For example: Orange.

- Background Color sets the color of the background for the specified element's box.  Colors can be specified in the same way as foreground color.

- Other elements of color to consider:
  - **Saturation**: the amount of gray in a color.  Maximum saturation would have no gray in the color.  Minimum saturation would be mostly gray.
  - **Brightness** refers to how much black is in a color.  Maximum brightness has no black in the color.  Minimum brightness would be very dark.
  - **Contrast** should be considered when picking your foreground and background colors. The more contrast there is between the two, the easier it will be to read the text.
  -**Opacity** is a value between 0.0 and 1.0. Rgba is the same as the rgb value was saw before except that it adds the alpha value which is used to specify opacity.

- **HSLA**: specifies the hue, saturation, lightness of a color, and opacity. 
  - **Hue** is measured from 0 to 360.
  - **Saturation** is measured from 0% to 100%, with 100% being full saturation and no shades of gray.
  - **Lightness** is measured from 0% to 100% with 0% being black and 100% being white.
  - **Alpha** is opacity being measuredd from 0.0 to 1.0.  
  - For example: hsla(0, 55%, 42%, 0.75)


[Home Page](https://slakeyj.github.io/)