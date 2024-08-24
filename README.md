
---

## flexifycss - A CSS Utility Library for Effortless Styling

**flexifycss** is a lightweight CSS utility library designed to streamline your styling process, making it faster and more efficient. It provides a comprehensive set of pre-defined utility classes that let you apply common styles with just a few words, resulting in cleaner, more readable code.

### Installation

To use flexifycss, first install it via npm:

```bash
npm install flexifycss
```

### Usage

Import flexifycss into your project:

```javascript
import React from 'react';
import 'flexifycss'; 

const FlexifyCssExample = () => {
  return (
    <div className="flex-row gap-10 p-20"> 
      <div className="w-50p h-200px back-color-blue-80 br-10"></div> 
      <div className="w-50p h-200px back-color-red-80 br-circle"></div> 
    </div>
  );
};

export default FlexifyCssExample;
```

**Explanation:**

- **Import React:** Imports the React library, necessary for creating React components.
- **Import flexifycss:** Imports your flexifycss.css file, containing the utility classes.
- **Create a Functional Component:** Defines a simple React component (`FlexifyCssExample`) to showcase usage.
- **JSX Structure:** Returns JSX, a syntax for writing HTML-like elements within JavaScript.
- **className:** Applies flexifycss utility classes to HTML elements:
  - `.flex-row`: Creates a flex container with row direction.
  - `.gap-10`: Adds a 10px gap between flex items.
  - `.p-20`: Applies 20px padding on all sides.
  - `.w-50p`: Sets the width to 50% of the parent container.
  - `.h-200px`: Sets the height to 200 pixels.
  - `.back-color-blue-80`: Sets the background color to a blue shade (defined in your CSS).
  - `.br-10`: Sets the border-radius to 10 pixels.
  - `.br-circle`: Sets the border-radius to 50% to create a circle.

**How to Use:**

1. Create a React project (using Create React App or similar).
2. Place the example code in a file, e.g., `FlexifyCssExample.js`.
3. Import and render the component in your app's root file (like `App.js`):

```javascript
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

4. Run your React app. You'll see the two colored divs rendered based on the flexifycss utility classes.

### Utility Classes

flexifycss offers a comprehensive set of utility classes, organized by category:

#### Display

- `.flex-row`: Sets display to flex with row direction.
- `.flex-column`: Sets display to flex with column direction.

#### Spacing

- **Padding:** `.p-1` to `.p-50`, `.pt-1` to `.pt-50`, `.pb-1` to `.pb-50`, `.pr-1` to `.pr-50`, `.pl-1` to `.pl-50`
- **Margin:** `.m-1` to `.m-50`, `.mt-1` to `.mt-50`, `.mb-1` to `.mb-50`, `.ml-1` to `.ml-50`, `.mr-1` to `.mr-50`
- **Gap:** `.gap-1` to `.gap-100`

#### Dimensions

- **Width:** `.w-1p` to `.w-100p` (percentage), `.w-5px` to `.w-1000px` (pixels), `.w-1s` to `.w-100s` (viewport width)
- **Height:** `.h-1p` to `.h-100p` (percentage), `.h-5px` to `.h-1000px` (pixels), `.h-1s` to `.h-100s` (viewport height)

#### Border

- **Border Radius:** `.br-1p` to `.br-100p` (percentage), `.br-1px` to `.br-100px` (pixels), `.br-circle`, `.br-none`
- **Border Width:** `.bw-1px` to `.bw-100px` (pixels), `.bw-thin`, `.bw-medium`, `.bw-thick`, `.bw-none`
- **Border Style:** `.bs-solid`, `.bs-dashed`, `.bs-dotted`, `.bs-double`, `.bs-groove`, `.bs-ridge`, `.bs-inset`, `.bs-outset`, `.bs-none`, `.bs-hidden`

#### Color

- **Color:**
  - `.color-black`, `.color-white`
  - **Predefined Color Profiles:** `.color-blue-100`, `.color-blue-90` to `.color-blue-10`, `.color-blueGreen-100`, `.color-blueGreen-90` to `.color-blueGreen-10`, `.color-red-100`, `.color-red-90` to `.color-red-10`, `.color-orange-100`, `.color-orange-90` to `.color-orange-10`, `.color-green-100`, `.color-green-90` to `.color-green-10`, `.color-gray-100`, `.color-gray-90` to `.color-gray-10`, `.color-purple-100`, `.color-purple-90` to `.color-purple-10`, `.color-yellow-100`, `.color-yellow-90` to `.color-yellow-10`
  - **User Defined Color Profiles:** `.color-primary`, `.color-secondary`, `.color-accent`, `.color-neutral`, `.color-error` (define these in your `:root`)

- **Opacity Variations:** Each predefined color has opacity variations from 10 to 90 (e.g., `.color-blue-80-50`)

#### Background

- **Background Color:**
  - `.back-color-black`, `.back-color-white`
  - **Predefined Color Profiles:** `.back-color-blue-100`, `.back-color-blue-90` to `.back-color-blue-10`, `.back-color-blueGreen-100`, `.back-color-blueGreen-90` to `.back-color-blueGreen-10`, `.back-color-red-100`, `.back-color-red-90` to `.back-color-red-10`, `.back-color-orange-100`, `.back-color-orange-90` to `.back-color-orange-10`, `.back-color-green-100`, `.back-color-green-90` to `.back-color-green-10`, `.back-color-gray-100`, `.back-color-gray-90` to `.back-color-gray-10`, `.back-color-purple-100`, `.back-color-purple-90` to `.back-color-purple-10`, `.back-color-yellow-100`, `.back-color-yellow-90` to `.back-color-yellow-10`
  - **User Defined Background Color Profiles:** `.back-color-primary`, `.back-color-secondary`, `.back-color-accent`, `.back-color-neutral`, `.back-color-error`
  - **Opacity Variations:** Each predefined background color has opacity variations from 10 to 90 (e.g., `.back-color-blue-80-50`)

#### Border

- **Border Color:**
  - `.bc-black`, `.bc-white`
  - **Predefined Color Profiles:** `.bc-blue-100`, `.bc-blue-90` to `.bc-blue-10`, `.bc-blueGreen-100`, `.bc-blueGreen-90` to `.bc-blueGreen-10`, `.bc-red-100`, `.bc-red-90` to `.bc-red-10`, `.bc-orange-100`, `.bc-orange-90` to `.bc-orange-10`, `.bc-green-100`, `.bc-green-90` to `.bc-green-10`, `.bc-gray-100`, `.bc-gray-90` to `.bc-gray-10`, `.bc-purple-100`, `.bc-purple-90` to `.bc-purple-10`, `.bc-yellow-100`, `.bc-yellow-90` to `.bc-yellow-10`
  - **User Defined Border Color Profiles:** `.bc-primary`, `.bc-secondary`, `.bc-accent`, `.bc-neutral`, `.bc-error`
  - **Opacity Variations:** Each predefined border color has opacity variations from 10 to 90 (e.g., `.bc-blue-80-50`)

#### Typography

- **Font Sizes:** `.font-xs` to `.font-6xl`
- **Line Heights:** `.line-height-xs` to `.line-height-6xl`
- **Font Weights:** `.font-w-100` to `.font-w-900`
- **Font Styles:** `.font-italic`, `.font-oblique`, `.font-normal`
- **Text Transform:** `.text-transform-none`, `.text-transform-uppercase`, `.text-transform-lowercase`, `.text-transform-capitalize`
- **Letter Spacing:** `.letter-spacing-0` to `.letter-spacing-100`
- **Word Spacing:** `.word-spacing-0` to `.word-spacing-100`
- **Font Variants:** `.font-variant-normal`, `.font-variant-small-caps`

#### Flexbox

- **Justify Content:** `.justify-start`, `.justify-center`, `.justify-end`, `.justify-between`, `.justify-around`, `.justify-evenly`
- **Align Items:** `.align-start`, `.align-center`, `.align-end`, `.align-baseline`, `.align-stretch`
- **

Align Content:** `.align-content-start`, `.align-content-center`, `.align-content-end`, `.align-content-between`, `.align-content-around`, `.align-content-evenly`
- **Align Self:** `.align-self-auto`, `.align-self-start`, `.align-self-center`, `.align-self-end`, `.align-self-baseline`, `.align-self-stretch`

#### Positioning

- **Position:** `.pos-static`, `.pos-relative`, `.pos-absolute`, `.pos-fixed`, `.pos-sticky`
- **Top, Right, Bottom, Left:** `.top-0` to `.top-100`, `.right-0` to `.right-100`, `.bottom-0` to `.bottom-100`, `.left-0` to `.left-100`

#### Transitions and Animations

- **Transitions:** `.transition-all`, `.transition-opacity`, `.transition-transform`, `.transition-color`, `.transition-background-color`
- **Animations:** `.animate-fade-in`, `.animate-slide-up`, `.animate-slide-down`, `.animate-bounce`, `.animate-spin`

#### Shadows

- **Box Shadows:** `.shadow-sm`, `.shadow-md`, `.shadow-lg`, `.shadow-xl`, `.shadow-2xl`, `.shadow-none`

### Contribution

Contributions are welcome! If you'd like to improve or add new features, please fork the repository and submit a pull request. Ensure that your code follows the existing style and includes tests where applicable.

### License

flexifycss is licensed under the GNU GENERAL PUBLIC LICENSE License. See the [LICENSE](LICENSE) file for more details.

### Contact

For any questions or feedback, please contact [Lati Tibabu](mailto:latitibabu2018@gmail.com).

---

**Happy Styling with flexifycss!**

