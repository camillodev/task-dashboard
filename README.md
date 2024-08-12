
# Task Dashboard

## Project Overview

The **Task Dashboard** is a Vue.js application designed to manage and track tasks. It demonstrates key Vue.js concepts and best practices using Composition API and Pinia for state management. The application includes features for adding, removing, and updating tasks, along with Vue Router for navigation and route protection.

## Requirements

- **Vue.js**: Use Vue.js with Composition API for component logic.
- **Pinia**: Manage global state with Pinia.
- **Vue Router**: Implement routing with route guards.
- **Directives**: Utilize Vue directives for DOM manipulation.
- **Watchers**: Observe and react to data changes.
- **Computed Properties**: Use for derived state.
- **Methods**: Implement functions for event handling and data manipulation.
- **Lifecycle Hooks**: Use lifecycle hooks for initialization and cleanup.
- **Slots**: Use slots for component customization.

## Requirement Features

### 1. Task Management
- [ ] **Add Task**: Add new tasks to the list.
- [ ] **Remove Task**: Delete tasks from the list.
- [ ] **Mark Task Complete**: Toggle the completion status of tasks.

### 2. Dynamic Task List
- [ ] **List Tasks**: Display tasks using `v-for` directive.
- [ ] **Show Message**: Use `v-if` to display a message when no tasks are present.
- [ ] **Bind Classes**: Use `v-bind` to dynamically set CSS classes based on task status.
- [ ] **Handle Events**: Use `v-on` to handle events like clicking buttons to mark tasks as completed.

### 3. State Management
- [ ] **Global Store**: Manage the task list state with Pinia.
- [ ] **Actions**: Create actions for adding, removing, and updating tasks.

### 4. Routing
- [ ] **Task Views**: Configure routes: Task List View, Task Details View. Create and edit must be modals
- [ ] **Route Guards**: Protect routes that require authentication.
- [ ] **Login page with [Clerk](https://clerk.com/)**

### 5. Lifecycle Hooks: Suggestions
- [ ] **Load tasks from local storage or API when the page is loaded**
- [ ] **Ensure that any resources (such as event listeners, timers, or subscriptions) are properly cleaned up or canceled before the component is removed from the DOM**

### 6. Use SLOTS for
- [ ] **Action Buttons**: add action buttons such as edit, complete, or delete
- [ ] **Additional Details**: such as due date or priority

## Checklist of Vue.js Concepts

- [ ] **Composition API**: Use `setup()`, `ref`, `reactive`, `computed`, and `watch`.
- [ ] **Pinia**: Implement global state management with Pinia.
- [ ] **Vue Router**: Configure routing with `vue-router`, including route guards.
- [ ] **Directives**:
  - [ ] `v-if`: Conditional rendering.
  - [ ] `v-for`: List rendering.
  - [ ] `v-bind`: Dynamic binding.
  - [ ] `v-on`: Event handling.
- [ ] **Watchers**: Observe changes to data and trigger actions.
- [ ] **Computed Properties**: Derive data based on state.
- [ ] **Methods**: Handle user interactions and state updates.
- [ ] **Lifecycle Hooks**:
  - [ ] `onMounted`: Initialize data.
  - [ ] `onBeforeUnmount`: Clean up resources.
- [ ] **Slots**: Customize components with slots.

## Examples of Functionality

- **Directives**:
  - `v-for`: List tasks with a dynamic rendering based on the state.
  - `v-if`: Display a message when the task list is empty.
  - `v-bind`: Apply CSS classes to tasks based on their completion status.
  - `v-on`: Add event listeners to buttons for marking tasks as completed.

- **Watchers**:
  - Track changes in the task list and update derived states like the number of remaining tasks.

- **Vue Router**:
  - Define routes for viewing the list of tasks, task details, and settings.
  - Implement route guards to ensure users are authenticated before accessing certain routes.

---

This README provides a clear overview of the project's requirements, features, and a detailed checklist of Vue.js concepts with practical examples.
