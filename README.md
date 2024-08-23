
---

## flexifycss - A CSS Utility Library for Effortless Styling

**flexifycss** is a lightweight CSS utility library designed to make styling faster and more efficient. It provides a collection of pre-defined utility classes that allow you to apply common styles with just a few words, making your code cleaner and more readable.

### Installation

To use flexifycss, first install it via npm:

```bash
npm install flexifycss
```

### Usage

Import flexifycss into your project:

```JavaScript
import React from 'react';
import 'flexifycss';

const FlexifyCssExample = () => {
  return (
    <div className="flex-row gap-10 p-20">
      <div className="w-50p h-200px back-color-blue80 br-10"></div>
      <div className="w-50p h-200px back-color-red80 br-circle"></div>
    </div>
  );
};

export default FlexifyCssExample;
```

Explanation:

- **Import React:** This imports the React library, essential for creating React components.
- **Import CSS:** This line imports your `flexifycss.css` file, which contains the utility classes you want to use.
- **Create a Functional Component:** `FlexifyCssExample` is a functional component in React, a simple way to define UI elements.
- **JSX Structure:** The component returns JSX, which is a syntax extension for JavaScript that lets you write HTML-like structures within your code.
- **className:** The `className` attribute is used to apply the flexifycss utility classes to HTML elements.
  - `.flex-row`: Creates a flex container with row direction.
  - `.gap-10`: Adds a 10px gap between flex items.
  - `.p-20`: Applies 20px padding on all sides.
  - `.w-50p`: Sets the width to 50% of the parent container.
  - `.h-200px`: Sets the height to 200 pixels.
  - `.back-color-blue80`: Sets the background color to a blue shade from your CSS.
  - `.br-10`: Sets the border-radius to 10 pixels.
  - `.br-circle`: Sets the border-radius to 50% to create a circle.

### How to Use:

1. Create a React project (using Create React App or similar).
2. Put the above code into a file, for example, `FlexifyCssExample.js`.
3. Import and render the component in your app's root file (like `App.js`):

```JavaScript
import React from 'react';
import FlexifyCssExample from './FlexifyCssExample';

function App() {
  return (
    <div>
      <FlexifyCssExample />
    </div>
  );
}

export default App;
```

Run your React app. You should see the two colored divs rendered according to the flexifycss utility classes.

### Utility Classes

**flexifycss** offers a wide range of utility classes for various styling aspects. Here are some examples:

**Display Modes**

- `.flex-row`: Sets display to flex with row direction.
- `.flex-column`: Sets display to flex with column direction.

**Padding**

- `.p-1` to `.p-50`: Applies padding values from 1px to 50px on all sides.
- `.pt-1` to `.pt-50`: Applies padding-top values from 1px to 50px.
- `.pb-1` to `.pb-50`: Applies padding-bottom values from 1px to 50px.
- `.pr-1` to `.pr-50`: Applies padding-right values from 1px to 50px.
- `.pl-1` to `.pl-50`: Applies padding-left values from 1px to 50px.

**Margin**

- `.m-1` to `.m-50`: Applies margin values from 1px to 50px on all sides.
- `.mt-1` to `.mt-50`: Applies margin-top values from 1px to 50px.
- `.mb-1` to `.mb-50`: Applies margin-bottom values from 1px to 50px.
- `.ml-1` to `.ml-50`: Applies margin-left values from 1px to 50px.
- `.mr-1` to `.mr-50`: Applies margin-right values from 1px to 50px.

**Gap**

- `.gap-1` to `.gap-100`: Applies gap values from 1px to 100px to elements within a flex container.

**Width**

- `.w-1p` to `.w-100p`: Sets width from 1% to 100% of the parent container.
- `.w-5px` to `.w-1000px`: Sets width in pixels with increments of 5px.
- `.w-1s` to `.w-100s`: Sets width in viewport widths (vw) with increments of 1vw.

**Height**

- `.h-1p` to `.h-100p`: Sets height from 1% to 100% of the parent container.
- `.h-5px` to `.h-1000px`: Sets height in pixels with increments of 5px.
- `.h-1s` to `.h-100s`: Sets height in viewport heights (vh) with increments of 1vh.

**Border Radius**

- `.br-1p` to `.br-100p`: Sets border-radius in percentage with increments of 1%.
- `.br-1px` to `.br-100px`: Sets border-radius in pixels with increments of 1px.
- `.br-circle`: Sets border-radius to 50% creating a circle.
- `.br-none`: Sets border-radius to 0.

**Border Width**

- `.bw-1px` to `.bw-100px`: Sets border-width in pixels with increments of 1px.
- `.bw-thin`, `.bw-medium`, `.bw-thick`: Sets border-width to default values.
- `.bw-none`: Sets border-width to 0.

**Border Style**

- `.bs-solid`, `.bs-dashed`, `.bs-dotted`, `.bs-double`, `.bs-groove`, `.bs-ridge`, `.bs-inset`, `.bs-outset`: Sets border-style to different styles.
- `.bs-none`, `.bs-hidden`: Sets border-style to none and hidden, respectively.

**Border Color**

- `.bc-black`, `.bc-white`: Sets border-color to black and white, respectively.
- `.bc-blue100` to `.bc-yellow10`: Sets border-color to predefined color variables with different opacities.

**Color**

- `.color-black`, `.color-white`: Sets color to black and white, respectively.
- `.color-blue100` to `.color-yellow10`: Sets color to predefined color variables with different opacities.

**Background**

- `.back-color-black`: Sets background-color to black.
- `.back-color-blue100` to `.back-color-yellow10`: Sets background-color to predefined color variables with different opacities.

**Font Sizes**

- `.font-xs` to `.font-6xl`: Applies font sizes based on predefined variables.

**Line Heights**

- `.line-height-xs` to `.line-height-6xl`: Applies line-height based on predefined variables.

**Font Weights**

- `.font-w-100` to `.font-w-900`: Sets font-weight to specific values.

**Font Styles**

- `.font-italic`, `.font-oblique`, `.font-normal`: Sets font-style to italic, oblique, and normal, respectively.

**Text Transform**

- `.text-transform-none`, `.text-transform-uppercase`, `.text-transform-lowercase`, `.text-transform-capitalize`: Applies text transform to elements.

**Letter Spacing**

- `.letter-spacing-0` to `.letter-spacing-100`: Sets letter-spacing in pixels with increments of 5px.

**Word Spacing**

- `.word-spacing-0` to `.word-spacing-100`: Sets word-spacing in pixels with increments of 5px.

**Font Variants**

- `.font-variant-normal`, `.font-variant-small-caps`: Sets font-variant to normal and small-caps, respectively.

**Justify Content**

- `.justify-start`, `.justify-center`, `.justify-end`, `.justify-between`, `.justify-around`, `.justify-evenly`: Sets justify-content property to different values.

**Align Items**

- `.align-start`, `.align-center`, `.align-end`, `.align-baseline`, `.align-stretch`: Sets align-items property to different values.

**Flex Property**

- `.flex-1` to `.flex-20`: Sets flex property with incremental values from 1 to 20.
- `.flex-auto`, `.flex-initial`, `.flex-none`: Sets flex property to auto, initial, and none, respectively.

**Flex Grow**

- `.flex-grow-1` to `.flex-grow-3`: Sets flex-grow property with incremental values from 1 to 3.
- `.flex-grow-auto`, `.flex-grow-0`: Sets flex-grow property to auto and 0, respectively.

**Flex Shrink**

- `.flex-shrink-1` to `.flex-shrink-3`: Sets flex-shrink property with incremental values from 1 to 3.
- `.flex-shrink-auto`, `.flex-shrink-0`: Sets flex-shrink property to auto and 0, respectively.

**Flex Basis**

- `.flex-basis-auto`, `.flex-basis-0`, `.flex-basis-1`, `.flex-basis-2`, `.flex-basis-3`, `.flex-basis-50`, `.flex-basis-100`: Sets flex-basis property to different

 values.

**Order Property**

- `.order-1` to `.order-20`: Sets order property with incremental values from 1 to 20.
- `.order-first`, `.order-last`, `.order-none`: Sets order property to first, last, and none, respectively.

**Text Alignment**

- `.text-left`, `.text-right`, `.text-center`, `.text-justify`: Sets text alignment to left, right, center, and justify, respectively.

**Overflow**

- `.overflow-auto`, `.overflow-hidden`, `.overflow-visible`, `.overflow-scroll`: Sets overflow property to auto, hidden, visible, and scroll, respectively.

**Box Shadow**

- `.shadow-xs` to `.shadow-6xl`: Applies box-shadow based on predefined variables.

**Opacity**

- `.opacity-0` to `.opacity-100`: Sets opacity in percentage increments of 10.

---

### Conclusion

**flexifycss** is a versatile and powerful CSS utility library that allows developers to quickly and efficiently style their web applications. By leveraging predefined utility classes, you can keep your CSS clean, organized, and easy to maintain.
