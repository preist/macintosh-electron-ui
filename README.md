# Macintosh Electron UI

Introducing an Electron UI toolkit that evokes a sense of nostalgia, for crafting desktop applications.

## Features

- **Nostalgic Design**: Enjoy the aesthetic appeal of the iconic Macintosh UI, reminiscent of the early days of personal computing.
- **Responsive Components**: Benefit from a collection of ready-to-use React components that adapt to various screen sizes and resolutions.
- **Intuitive User Experience**: Create applications with a user-friendly interface, allowing users to easily navigate and interact with your app.
- **Customizable**: Tailor the UI to match your application's specific requirements with ease, using the provided configuration options and styles.
- **React and TypeScript**: Leverage the power of React's component-based architecture and TypeScript's type safety for a robust and maintainable codebase.

## Getting Started

Follow the steps below to get started with the **Macintosh Electron UI** project:

1. **Installation**: Clone the repository and install the project dependencies using npm or yarn.

```bash
git clone https://github.com/preist/macintosh-electron-ui.git
cd macintosh-electron-ui
npm install
```

2. **Development**: Start the development server to view the demo application in your browser.

```bash
npm run start
```

3. **Build**: Build the project to generate the production-ready files in the `build` folder.

```bash
npm run build
```

4. Usage: Use the components in your own project by importing them from the `dist` folder.

```typescript
import React from 'react';
import { Window, Button } from 'macintosh-electron-ui';

const App: React.FC = () => {
  return (
    <Window title="My Macintosh App">
      <Button>Hello, Macintosh!</Button>
    </Window>
  );
};

export default App;
```


## Contributing

Contributions to the Macintosh Electron UI project are welcome! If you encounter any bugs, have feature requests, or would like to contribute improvements, please follow our guidelines outlined in the **CONTRIBUTING.md** file.

## License

The Macintosh Electron UI project is licensed under the **MIT License**. Feel free to use, modify, and distribute this project in accordance with the terms specified in the license