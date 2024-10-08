# Unifi Starter Application

This is a simple web application that serves as a launcher for the Unifi Works platform. The application receives user information via messages from a parent window and enables the user to launch the Unifi app with session-specific data.

## Features

- **Tailwind CSS for Styling:** The project uses Tailwind CSS to create a responsive, minimalistic design.
- **Session Handling:** The application listens for incoming messages from the parent window to retrieve user information and enable the "Launch Application" button.
- **Spinner Indicator:** A loading spinner is displayed until the user information is successfully received, parsed, and the application is ready for launch.
