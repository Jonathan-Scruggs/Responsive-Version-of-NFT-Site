# Responsive-Site
- A good padding for buttons is 0.5em 1em. This makes it proportionally to the elements font size.
- Common to set a margin-bottom to equal 1em.
- Font Size with "em" is relative to the nearest ancestor.
- Whilst padding/margin with em is relative
- Compounding Issues With Font Sizes With Em:
  - Nested elements with em can cause compounding effects. Changing one part of the nets can cause confusing CSS styling
  - Can be fixed by using the rem unit.
- rem stands for "Root em" and is always relative to the root <html> element. Calculate exactly same as em.
- rem unit fixes any compounding effects.
- line height is used to set the distance between lines of text.
  - The recommended practice for responsive design is to set line height to a unitless value.
  - A good rule of thumb is to set the line-height to 1.5 times the font-size of that element.
  - Ex.) line-height: 1.5; is 150% larger than the font-size
  - Ensures it always perserves this ratio in regards to the font-size
- How to Decide What Units To Use:
  - Font Sizes: Use rem units! No compounding effects and more predictable.
  - Margin and Padding: Use em units! Proportional scaling and based on elements current font-size.
  - Line Height: Unitless number values.
  - Width: Use %. Flexible containers and flexible images.
  - Max-Width: Use px to set a hardcoded max with. Easier to manage and ensures consistency over larger screen sizes.
- Media Query Syntax:
  - @media (max-width: 800px){
    body {
      color: etc
      } 
    }
  - The condition that hte query is checking goes inside the brackets
  - Essentially this media query is asking if the browser is less than or equal to 800px then apply this css.
  - Can use the "and" keyword to make it so css is applied to a range of values.
- Mobile-first CSS:
    - Write your base CSS with mobile devices in mind first
    - Use media queries to adjust the layout and design for wider screens
    - Mobile layouts and style is usually pretty simple.
- Common Breakpoints:
    - 480px, for mobile devices like phones
    - 768px, for tablets
    - 1024px, laptops/smaller monitors
    - 1280px is for desktops.
- Mobile First Means Content First:
  - When designing for mobile devices place the most important content front and center
  - Don't waste screen space on white space.
- On Mobile its import to display buttons as block level elements:
  - This makes the buttons more accessbile as tapping is not a precise as a mouse cursor.
- We Should also change font-size for mobile devices:
  -  make text smaller
  -  Then on larger screens increase the font-size.
- flex-basis:
  - Sets the initial size
- flex-grow:
  - Flex items grow to take up a even portion of free space.
- flex: a shorthand property to set flew-grow flex-basis
## What I learnt
- Thinking responsively
- %, em, rem
- Media queries and mobile first design
- flex-wrap and gap
- flex-basis, flex-grow and flex.
  
