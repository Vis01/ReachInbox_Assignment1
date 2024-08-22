# Project Name

This project is a web application designed to provide a seamless user experience for logging in via Google, managing onebox threads, and replying to messages. The application is built using React.js, Tailwind CSS, Vite, and TypeScript, and it includes both light and dark mode themes.

## Features

1. **Google Login:**
   - Users can log in using their Google account.
   - Upon successful login, users are redirected to the onebox screen.

2. **Onebox Screen:**
   - Displays a list of threads fetched from the `/onebox/list` API.
   - Allows users to view individual threads using the `GET /onebox/:thread_id` API.
   - Supports deleting threads with the `DELETE /onebox/:thread_id` API.

3. **Keyboard Shortcuts:**
   - Pressing **D** deletes the selected thread.
   - Pressing **R** opens the reply box for the selected thread.

4. **Custom Text Editor:**
   - Includes custom buttons like **SAVE** and **Variables**.
   - Provides rich text editing capabilities for composing replies.

5. **Reply Functionality:**
   - Users can send replies via the `POST /reply/:thread_id` API.
   - The reply includes fields such as `from`, `to`, `subject`, and `body`.

6. **Light and Dark Mode:**
   - Users can switch between light and dark themes for better accessibility and user preference.

## Technologies Used

- **React.js**: JavaScript library for building user interfaces.
- **Tailwind CSS**: Utility-first CSS framework for rapid UI development.
- **Vite**: Next-generation frontend tooling for faster builds.
- **TypeScript**: Typed superset of JavaScript for improved development experience.

## Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name
