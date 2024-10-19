
TODO App Documentation

The app's primary goal is to help users organize and manage their tasks efficiently. The app uses SQLite for local data storage, ensuring that tasks are saved even when the app is closed.
Group Lists:

Users can create multiple task groups to organize tasks into categories (e.g., Work, Personal, Shopping).
Each group helps to keep tasks structured and easy to manage.


Todo Lists:

Within each group, users can add and manage multiple tasks.
Each task includes a title and a description to provide more detail.


Task Management:

Users can mark tasks as completed or pending to keep track of progress.
Tasks can be edited or deleted as needed, giving users full control over their lists.

User Interface:

The app features a clean and modern user interface inspired by design trends from Dribbble.
The design is optimized for simplicity and ease of navigation, with a focus on providing a seamless user experience.
//

Installation and Setup
To run the application, users must have a compatible environment set up. The app is built with React Native and Expo, which allows it to run on both Android and iOS platforms. The SQLite integration handles local data storage on the device.

How the App Works
The app uses SQLite for managing all task data, ensuring that each task and group is saved to the local database. This means that users do not need an internet connection to access their tasks. Data is persisted across sessions, making the app reliable for offline use.

// 

Screens and Navigation
Home Screen:

The home screen displays all task groups with the option to add new ones.
Users can easily navigate between different groups to see their tasks.
Todo List Screen:

This screen displays all the tasks within a selected group, allowing users to manage their to-dos effectively.
Task Creation/Editing Screen:

Users can create new tasks or edit existing ones. The screen provides fields for both the task title and description.
Task Details Screen:

This screen shows detailed information about a task, including options to edit or delete it.

