---
status: pending
title: Todo App
---

1. Create the shared task type at /app/src/types/todo.ts. Outcome: a reusable definition for a task that includes a unique id, the task text, and whether it is completed.

2. Create a custom hook for managing tasks at /app/src/hooks/useTodos.ts. Outcome: centralized logic to add a task, toggle a task's completed state, delete a task, and clear all completed tasks. Tasks are saved to the browser's local storage so they persist across page refreshes.

3. Create an input component for adding tasks at /app/src/components/TodoInput.tsx. Outcome: a text field with an "Add" button; pressing Enter or clicking Add creates a new task, and the field clears afterward. Empty entries are ignored.

4. Create a single task row component at /app/src/components/TodoItem.tsx. Outcome: shows a checkbox, the task text (struck through when completed), and a delete button that appears for removing that task.

5. Create the task list component at /app/src/components/TodoList.tsx. Outcome: renders all tasks using the task row component, and shows a friendly empty-state message when there are no tasks.

6. Create a filter control component at /app/src/components/TodoFilter.tsx. Outcome: buttons to view All, Active, or Completed tasks, with the active choice visually highlighted, plus a count of remaining tasks and a "Clear completed" action.

7. Create the main page at /app/src/pages/TodoPage.tsx. Outcome: assembles the title, input, filter controls, and task list into a centered card layout using the task hook to wire everything together.

8. Update /app/src/App.tsx to render the todo page. Outcome: the app displays the full todo experience on load.

9. Confirm /app/src/styles/global.css starts with the Tailwind import and is imported once in /app/src/main.tsx. Outcome: styling is applied correctly across the app.

10. Apply a clean, modern visual style throughout using Tailwind utilities — a soft background, a centered white card, clear spacing, hover and focus states on buttons and inputs, and readable typography. Outcome: the todo app looks polished and is comfortable to use on both mobile and desktop.
