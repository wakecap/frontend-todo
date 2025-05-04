# Task Description: Frontend Engineer - Todo Application

## Objective

Develop a web-based Todo application using **ReactJS** with the given stack. The goal is to evaluate your coding skills, architectural decisions, state management expertise, and ability to write documentation and tests.

---

## Technical Stack Requirements

- ReactJS, NextJS, VueJS, or using any UI Framework.
- Zustand (State Management) (if needed)
- Tailwind CSS
- ShadCN (UI Components)
- TypeScript
- Axios or Fetch (for API requests if necessary)
- Jest (for Unit Testing)
- Zod or Yup (for Form Validation)
- Vite or Create-React-App (Project Setup)
- Storybook (for Documentation)
- ArcGIS JavaScript SDK 4.x (for Geo-Spatial Features)

---

## Business Requirements

The Todo application should support the following functionalities:

### 1. Task Management

- Users should be able to **add** new tasks.
- Users should be able to **edit** tasks by double-clicking on them.
- Users should be able to **delete** tasks (Soft Delete).
- Users should be able to **mark tasks as completed** by checking a checkbox.
- Users should be able to **view tasks in a paginated list**.
- Users should be able to **view tasks on a map**.
  - Visualize tasks on a map, using markers to indicate their locations.
  - Interact with the map, including:
    - Clicking markers to view task details.
    - Creating new tasks by clicking on the map.
    - Updating a task’s location by dragging its marker.
  - Keep the map and the task list synchronized (e.g. changes on the map should reflect in the list and vice versa).
  - Support spatial filtering (By Zoom-in, Zoom-out, etc).
  - Visually distinguish between completed and incomplete tasks.
> **Ensure the architecture is extensible—your solution should support other geolocated entities in the future (e.g., workers, documents, sensors), not just tasks.**

### 2. UI & UX

- A header should display the following:
  - Count of **uncompleted tasks**.
  - Count of **completed tasks**.
  - Count of **deleted tasks**.
- An **"Add Task"** button should be available in the header.
- Clicking on "Add Task" should open a **modal** with:
  - A **textarea** for entering the task.
  - A **save** button.
  - A **cancel** button.
  - An **interactive map** for location selection.
- The same modal should be used for editing a task.
- You can use [UntitledUI](https://www.untitledui.com/free-figma-ui-kit) as a reference for the UI.
- Use your imagination to design the todo app.

### 3. Pagination Support

- The tasks list should support **pagination** to handle a large number of tasks efficiently.

---

## API Endpoints

Please check the `postman_collection.json` for all available endpoints. Also, check and read the `README.md` file under `/api` folder for more details.

## Deliverables

### 1. Fully Functional Todo Application

- Please make sure to implement all features as described.
- Use the specified tech stack.
- Implement geospatial features using ArcGIS JavaScript SDK.

### 2. Code Quality & Best Practices

- Follow best practices for **code organization, modularity, and reusability**.
- Use **Zod or Yup** for form validation.
- Use **TypeScript** effectively.
- Maintain a **clean folder structure**.
- Use Prettier for code formatting (Airbnb Style).
- Configure ESLint for code linting.
- Implement proper error handling for geospatial operations.

### 3. Unit Tests

- Write **unit tests using Jest** for critical functionalities.
- Ensure at least **80% test coverage**.
- Include tests for geospatial features and map interactions.

### 4. Documentation

- Provide **clear setup instructions** on how to install and run the application.
- Document all components using **Storybook**:
  - Include component variations and states
  - Document props and their types
  - Provide usage examples
- Explain architectural choices and state management decisions.
- Describe any **trade-offs** made during development.
- Include API documentation if any API interactions are used.
- Document geospatial features and ArcGIS integration.

### 5. Git Repository

- Host the project on a **public GitHub repository**.
- Follow a **structured commit history**.
- Include a well-written **README.md** file.

### 6. Nice to Have (Optional)

- Support the Internationalization (i18n) feature.
- Support the Dark Mode feature.
- Implement task clustering on the map.

---

## Evaluation Criteria

- **Code Quality & Best Practices**: Clean, maintainable, and modular code.
- **Functionality**: Implementation of all required features.
- **State Management**: Proper use of Zustand.
- **UI/UX**: Use of Tailwind and ShadCN for a polished UI.
- **TypeScript Usage**: Effective use of types and interfaces.
- **Form Validation**: Proper implementation using Zod or Yup.
- **Testing**: Well-written unit tests with good coverage.
- **Documentation**: Clear, structured, and comprehensive documentation including Storybook implementation.
- **Performance & Scalability**: Efficient rendering and API handling.
- **Architecture & File Structure**: Well-organized project and follows good architecture.
- **ArcGIS Integration**: Proper use of ArcGIS JavaScript SDK 4.x features.
- **Geospatial Features**: Implementation of location-based features and spatial queries.
- **Map Interaction**: Intuitive map-based task management and filtering.

---

## Submission Instructions

1. Upload the project to a public **GitHub repository**.
2. Include a **detailed README** with setup instructions.
3. Provide a **brief documentation file** explaining the architecture, state management, and decisions.
4. Submit the GitHub repository link within the given timeframe.

---

Good luck, and happy coding! 🚀
