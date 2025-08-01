📝 Todo App

Description:

This application is designed for creating, editing, deleting, and managing tasks (todos). You can quickly add a new task using the input field.

Key Features:

1) Create a task — enter the title and press Enter.

2) Manage task status — toggle the status of a task using the radio button, or change the status of all tasks at once using the arrow button.

3) Edit task title — double-click on a task's title to edit it.

4) Filter by status — filter tasks by status: All / Active / Completed.

5) Bulk delete — remove all completed tasks with a single click.

Technologies Used:

1) REST API — interaction with the server is handled using fetch requests.

2) Custom hooks — used to separate logic related to API communication and filtering.

3) Bulma — styling is done using the Bulma CSS framework.

4) React hooks — useState and useEffect are used to manage loading states and handle possible errors for a better user experience.

5) Promise.allSettled — used for bulk status updates or deletions, allowing handling of both successful and failed requests.

🚀 Getting Started:

To run the project locally, follow these steps:

- Clone the repository:
  git clone 'repository-url'

- Install dependencies:
  npm install

- Start the development server:
  npm start

