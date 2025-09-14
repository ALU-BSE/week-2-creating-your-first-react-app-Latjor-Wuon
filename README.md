[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/_ixf7gdX)
[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=20484003)

# react-dev-week-2-react-app

### Guided Learning Activity: Creating Your First React App with TypeScript and Vite

**Goal:** Build a simple React app that displays a heading and a paragraph of text using a custom component, styled with CSS.

## Assignment Completed

This repository contains the completed React + TypeScript + Vite assignment.

### Features

- **MyComponent**: React functional component with TypeScript
- **Custom Styling**: CSS with lightblue background and navy text
- **App Integration**: MyComponent used in App.tsx
- **TypeScript Support**: Full TypeScript configuration
- **Vite Development**: Development server with HMR

### Getting Started

1. **Install dependencies:**
   ```bash
   npm install
   ```

2. **Start the development server:**
   ```bash
   npm run dev
   ```

3. **Open your browser and visit** `http://localhost:5173/`

### Project Structure

```
my-first-react-app/
├── src/
│   ├── MyComponent.tsx    # Custom React component
│   ├── MyComponent.css    # Component styling
│   ├── App.tsx           # Main app component
│   ├── App.css           # App styling
│   └── main.tsx          # Entry point
├── index.html            # Main HTML file
├── package.json          # Dependencies and scripts
├── tsconfig.json         # TypeScript configuration
└── vite.config.ts        # Vite configuration
```

### Assignment Tasks

**Step 1: Set up the Project with Vite**
- Created project with `npm create vite@latest my-first-react-app -- --template react-ts`
- Installed dependencies with `npm install`
- Configured Vite development server

**Step 2: Understand the Project Structure**
- Analyzed Vite-generated project structure
- Identified key files and their purposes

**Step 3: Create Your First Component**
- Created `MyComponent.tsx` with proper TypeScript typing
- Used `React.FC` for functional component type
- Implemented JSX structure with heading and paragraph

**Step 4: Use Your Component in App.tsx**
- Imported MyComponent in App.tsx
- Rendered MyComponent within App component
- Updated App.tsx to use the custom component

**Step 5: Style Your Component**
- Created `MyComponent.css` with required styles
- Added lightblue background, navy text color
- Imported CSS in MyComponent.tsx
- Added centering styles to App.css

**Step 6: Run and View**
- Development server running on http://localhost:5173/
- Component displays correctly with styling
- Hot module replacement working

### Technologies Used

- **React 18**: Modern React with hooks
- **TypeScript**: Static typing and modern JavaScript features
- **Vite**: Fast build tool and development server
- **CSS3**: Custom styling and layout
- **ESLint**: Code linting and quality

### Code Examples

**MyComponent.tsx:**
```typescript
import React from 'react';
import './MyComponent.css';

const MyComponent: React.FC = () => {
  return (
    <div className="my-component">
      <h1>Hello from MyComponent!</h1>
      <p>This is a paragraph of text within my component.</p>
    </div>
  );
};

export default MyComponent;
```

**MyComponent.css:**
```css
.my-component {
  background-color: lightblue;
  padding: 20px;
  border: 1px solid blue;
  border-radius: 5px;
  text-align: center;
}

.my-component h1 {
  color: navy;
}

.my-component p {
  font-size: 16px;
}
```

### Learning Outcomes

- Understanding React functional components
- TypeScript integration with React
- CSS styling in React applications
- Vite development workflow
- Component composition and structure

### Further Exploration

- **Props:** Learn how to pass data into components using props
- **State:** Explore how to manage dynamic data within your components using state
- **More Complex Styling:** Look into styled-components or other CSS-in-JS solutions
- **Vite Documentation:** [https://vitejs.dev/](https://vitejs.dev/)
- **React Documentation:** [https://react.dev/](https://react.dev/)
- **TypeScript Documentation:** [https://www.typescriptlang.org/](https://www.typescriptlang.org/)

### Author

**Latjor-Wuon** - React + TypeScript + Vite Assignment

---

*This project was created as part of the ALU Full-Stack Web Development program.*