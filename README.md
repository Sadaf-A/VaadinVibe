# VaadinVibe
VaadinVibe is a dynamic web application built using the Vaadin framework. It features a user-friendly 'Register Form' with before and after submission visuals. The project structure adheres to Maven standards, offering easy command-line and IDE-based deployment. Explore its intuitive interface for seamless data management.

## Register Form

| Before Submitting | After Submitting |
|-------------------|------------------|
| ![Before Submitting](https://github.com/Sadaf-A/learning-vaadin/assets/119438857/dbc8c6cb-e360-4932-aa26-615ae98ba4ad) | ![After Submitting](https://github.com/Sadaf-A/learning-vaadin/assets/119438857/35e0c4ee-dceb-4195-bdb1-1a0f13e74b70) |

## Running the Application

The project is a standard Maven project. To run it from the command line, type `mvnw` (Windows) or `./mvnw` (Mac & Linux), then open http://localhost:8080 in your browser.

You can also import the project into your IDE of choice as you would with any Maven project. Read more on [how to import Vaadin projects to different IDEs](https://vaadin.com/docs/latest/guide/step-by-step/importing) (Eclipse, IntelliJ IDEA, NetBeans, and VS Code).

## Project Structure

| Directory/File                 | Description                                                         |
|--------------------------------|---------------------------------------------------------------------|
| `MainLayout.java`              | Navigation setup (side/top bar and main menu) using App Layout.    |
| `views` (in `src/main/java`)   | Server-side Java views of your application.                         |
| `views` (in `frontend/`)       | Client-side JavaScript views of your application.                  |
| `themes` (in `frontend/`)      | Custom CSS styles for your application.                             |
| `UserTableView.java`           | User table view to display user data. (Added as an enhancement)     |
