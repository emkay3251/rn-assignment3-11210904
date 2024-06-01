# rn-assignment3-11210904

## Description

This repository contains a React Native application designed to recreate a UI mockup for a task management application. The app includes essential core components and features like viewing categories, listing ongoing tasks, and an intuitive user interface.

## Components

### 1. **App**
The main component that sets up the navigation and renders the `TaskManager` component.

### 2. **TaskManager**
The core component that contains the main structure of the application, including the category list, task list, and input form for new tasks.

### 3. **CategoryList**
A custom component that renders a list of categories using the `FlatList` component. Each category is represented by a button with an icon and label.

### 4. **TaskList**
A custom component that renders the list of ongoing tasks using the `FlatList` component. Each task is displayed with a title and description.

### 5. **TaskInput**
A custom component that provides a form with `TextInput` fields for adding new tasks. It includes a submit button to add the task to the list.

### 6. **TaskItem**
A custom component representing each task in the task list. It displays the task title, description, and an icon.

### 7. **CategoryItem**
A custom component representing each category in the category list. It displays the category icon and name.

### 8. **Header**
A custom component that displays the application's header, including the title and a settings icon.

## Screenshots

![Home Screen](my-app/assets/images/localhost_8081 and 2 more pages - Personal - Microsoft​ Edge 6_1_2024 2_44_21 AM.png)

## Setup and Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/rn-assignment3-11210904.git
    ```

2. **Navigate to the project directory:**
    ```bash
    cd rn-assignment3-11210904
    ```

3. **Install the dependencies:**
    ```bash
    npm install
    ```

4. **Run the application:**
    ```bash
    npm start
    ```

## Development Steps

1. **Project Setup:**
    - Initialized a new React Native project.
    - Set up the directory structure.

2. **Create Core Components:**
    - Created `CategoryList`, `TaskList`, `TaskInput`, `TaskItem`, `CategoryItem`, and `Header` components.
    - Ensured each component used necessary core components (`View`, `Text`, `ScrollView`, `TextInput`, `Stylesheet`, `Button`, `FlatList`, `Image`).

3. **Implement Category List:**
    - Added eight categories such as Exercise, Study, Code, Cook, etc.
    - Styled the categories to match the provided UI design.

4. **Implement Task List:**
    - Added a list of 15 ongoing tasks.
    - Styled the tasks to match the provided UI design.

5. **Add Task Input Form:**
    - Created a form with `TextInput` fields for task title and description.
    - Added a submit button to add the new task to the task list.

6. **Styling:**
    - Applied custom styles using `Stylesheet` to match the UI mockup.
    - Ensured responsiveness and consistency across different screen sizes.

7. **Testing:**
    - Tested the application on both iOS and Android devices.
    - Fixed any bugs and ensured smooth functionality.

8. **Documentation:**
    - Created screenshots of the application.
    - Wrote this README file.

## Resources

- UI Design: [Figma File](https://www.figma.com/design/nk9YKIdz4RFypdwF9mtQTm/DCIT-202---Assignment-3?node-id=1-5&t=MJeOiPfQAvChwNdX-1)
- React Native Documentation: [React Native](https://reactnative.dev/)

## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.

## License

This project is licensed under the MIT License.
