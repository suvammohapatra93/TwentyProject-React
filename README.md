# 25 React Projects

This is a repository that includes 20 small projects, all built using React, Tailwind CSS, JavaScript, and CSS. These small projects are unified to form a larger project that showcases various skills and functionalities.

Each project is built as a separate component within a single React application. These mini-projects can serve as learning resources, inspiration, or building blocks for larger applications.

## Features

- Built with React for component-based architecture.
- Styled using Tailwind CSS and vanilla CSS for responsive and clean UI.
- JavaScript is used to handle dynamic content and interactions.
- React Icons are used for easy integration of icons.

## Projects Included

1. **Accordion** - A simple accordion component to toggle content visibility.
2. **Custom Modal Popup** - A custom modal popup implementation.
3. **Custom Tabs** - Custom tab navigation between different sections.
4. **Feature Flag** - Feature flag management to enable/disable features.
5. **GitHub Profile Finder** - Search and display GitHub user profiles.
6. **Image Slider** - A simple image slider with manual navigation.
7. **Light/Dark Mode** - Toggle between light and dark themes.
8. **Load More Data** - Load more data functionality with a button click.
9. **QR Code Generator** - Generate QR codes from input text.
10. **Random Color (Using RGB and HEX Value)** - Generate random colors and display both RGB and HEX values.
11. **Scroll Indicator** - A progress bar that indicates how much of the page has been scrolled.
12. **Scroll to Top and Bottom** - Buttons to scroll to the top or bottom of the page.
13. **Search AutoComplete With API** - A search input with autocomplete suggestions fetched from an API.
14. **Star Rating** - A star rating component using React Icons.
15. **Tic-Tac-Toe** - A classic Tic-Tac-Toe game.
16. **GitHub User Finder** - Another GitHub user search component.
17. **Tree View** - A tree view component to display hierarchical data.
18. **Use Fetch** - A custom hook to fetch data from an API.
19. **Use Outside Click** - A custom hook to handle clicks outside a specified component.
20. **Use Window Resize** - A custom hook to track window resize events.

## Installation

1. Create the React application:

   ```bash
   npx create-react-app 25-projects-react
   cd 25-projects-react
   ```

2. Install the necessary dependencies:

   ```bash
   npm install
   ```

3. Install React Icons for using icons in the projects:

   ```bash
   npm install react-icons
   ```

4. Start the development server:

   ```bash
   npm start
   ```

## Usage

Each project is a component inside the `src` folder. You can navigate between projects by importing the desired component into `App.js`.

For example, to display the **Star Rating System**:

```javascript
import StarRating from "./components/StarRating";

function App() {
  return (
    <div className="App">
      <StarRating />
    </div>
  );
}

export default App;
```
