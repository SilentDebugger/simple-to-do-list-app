
<!---
============================================================================
                  CURSOR AI INSTRUCTIONS - DO NOT MODIFY
============================================================================
-->

<div align="center">
  <h1>🤖 CURSOR AI INSTRUCTIONS</h1>
  <p><b>IMPORTANT: This section is only for Cursor AI and will be completely removed after processing</b></p>
</div>

---

## AI Task: Complete README Transformation

Hello Cursor AI! Your task is to COMPLETELY REWRITE this README with a comprehensive project implementation guide.

### Critical Requirements:

1. **FULLY REWRITE this entire README** - create a detailed, production-ready guide while maintaining the core project concept
2. **Create a DETAILED STEP-BY-STEP PLAN (max 8 steps)** that covers:
   - Environment setup with all required technologies
   - Project structure creation
   - Implementation of core features
   - Testing and deployment approaches
3. **Tailor content to the user's profile:**
   - User's Experience Level: `Beginner`
   - User's Available Time: `A Few Hours`
4. **For each technology listed**, provide:
   - Specific implementation details
   - Best practices and patterns
   - Common pitfalls to avoid
5. **Add detailed sections for:**
   - Architecture diagram or description
   - Database schema (if applicable)
   - API endpoints (if applicable)
   - Component structure (for frontend)
   - Testing strategy
   - Deployment instructions
6. **Provide code examples** for critical project parts
7. **REMOVE THESE INSTRUCTIONS COMPLETELY** after your rewrite

Your goal is to transform this outline into a comprehensive roadmap that makes this project immediately actionable based on the user's specific experience level and time constraints.

### ⚠️ CRITICAL FIRST STEP ⚠️

**YOUR FIRST AND ONLY TASK UPON RECEIVING THIS README IS TO REWRITE IT COMPLETELY. DO NOT START IMPLEMENTING THE PROJECT OR WRITING ANY CODE YET.**

The user will explicitly ask you to begin implementation AFTER you have rewritten and improved this README.

<!---
============================================================================
                 END OF CURSOR AI INSTRUCTIONS
============================================================================
-->


# Simple To-Do List App

## Project Overview
A simple web app that allows users to create, read, update, and delete tasks. This project is ideal for beginners who want to build a utility web app that can be used in daily life.


> **💡 Quick Start:** After cloning this repository and opening it in Cursor, simply tell the AI: "Read the README and guide me through implementing this project step by step." Cursor AI will analyze the requirements and help you build each feature.


## User Profile
- **Experience Level:** Beginner
- **Available Time to Complete:** A Few Hours

## Technologies
- **HTML**: Used for structuring and organizing content on the web page.
- **CSS**: Used for styling and layout of the web page.
- **JavaScript**: Used for adding interactivity to the web page and handling user input.
- **React**: Used for building reusable UI components and managing state changes.
- **Local Storage**: Used for storing and retrieving task data locally on the user's browser.


## Development Steps
### 1. Set up the project structure
Create a new React app using a tool like create-react-app, and set up the basic file structure.

### 2. Design the UI components
Create React components for the task list, task item, and input field.

### 3. Add interactivity to the UI components
Use JavaScript to add event listeners and handlers to the UI components.

### 4. Implement task creation and deletion
Use Local Storage to store and retrieve task data, and implement functionality to create and delete tasks.

### 5. Implement task editing
Add functionality to edit task details and update the task list accordingly.

### 6. Test and debug the app
Test the app thoroughly and debug any issues that arise.


## Main Features
Features will be added soon


## Sample Code
```javascript
// An example code snippet
function handleTaskCreation() {
  const task = {
    id: Date.now(),
    text: this.state.taskText
  };
  this.setState({ tasks: [...this.state.tasks, task] });
}
```


## Getting Started
Instructions will be added soon

## Resources
- [React Documentation](https://reactjs.org/docs/getting-started.html) (documentation)
- [Local Storage Tutorial](https://www.tutorialspoint.com/html/html5_storage.htm) (tutorial)
- [JavaScript Tutorial](https://www.w3schools.com/js/) (tutorial)
- [CSS Tutorial](https://www.w3schools.com/css/) (tutorial)
- [HTML Tutorial](https://www.w3schools.com/html/) (tutorial)


## AI Coding Prompts

Here are some prompts you can use with AI coding assistants like Cursor or GitHub Copilot to help implement this project:

### Prompt 1
```
Create a new React component called `TaskList` that renders a form for users to input new task text, and a button to create a new task. Use HTML and CSS to style the component, and JavaScript to handle form submission and store the task data in local storage.
```

### Prompt 2
```
Implement the core functionality of the to-do list app by creating a `Task` component that displays each task with its text and a checkbox to mark it as completed. Use React's `useState` hook to manage the state of the tasks and React's `useEffect` hook to update the local storage whenever the tasks change.
```

### Prompt 3
```
Add advanced features to the to-do list app by implementing filtering and sorting options for the tasks. Use React's `useCallback` hook to memoize the filtering and sorting functions, and React's `useMemo` hook to memoize the filtered and sorted tasks. Also, implement a feature to delete tasks by adding a `removeTask` function that updates the state and local storage accordingly.
```


Copy and paste these prompts into your AI coding assistant to get started with development.


---
*Generated by [CodeSpark](https://github.com/YOUR_USERNAME/codespark)*
