# Pella Dashboard

This project is a simple admin dashboard built for managing servers hosted on Pella. The dashboard includes a sidebar with login controls, server management features, and a responsive layout.

## Features

- **Login System**: Allows admins to login using predefined credentials.
- **Server Management**: Once logged in, admins can:
  - Delete a server
  - Start a server
  - Restart a server
  - Stop a server
  - Visit a server
- **Responsive Design**: The dashboard layout adjusts to different screen sizes and includes a sidebar that can be toggled.

## Layout

The layout consists of two main sections:
1. **Sidebar**: Contains the login form and server management controls.
2. **Main Content Area**: Displays a list of hosted servers with project details.

### Sidebar

- The sidebar is hidden by default and can be toggled using the switch in the top-right corner.
- After logging in with valid credentials (`admin` / `password`), the server management controls are revealed.
- The login form disappears once authenticated.

### Main Content Area

- The main content area showcases a list of servers hosted on Pella. Each server is represented by a card containing the server's name and status.

## Usage

To run this dashboard locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/username/pella-dashboard.git
