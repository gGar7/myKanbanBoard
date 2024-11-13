## Project View

<kbd>![](https://res.cloudinary.com/anshumxn09/image/upload/v1692799526/test/quickSell2_pjyru9.png)</kbd>
🗂️ Kanban Board
A responsive and dynamic Kanban board application built with React JS and Redux Toolkit, designed to streamline task management by organizing tasks efficiently. This board supports grouping, sorting, and an intuitive loading animation for a seamless user experience.

🌟 Features
🗄️ Dynamic Grouping: Group tasks by status, user, or priority.
📝 Ordering Options: Sort tasks within each group by title or priority.
💻 Responsive UI: Designed with React Icons and CSS for a polished look and feel.
⏳ Loading Animation: Displays a spinner while fetching data from the backend API.
📦 State Management: Powered by Redux Toolkit for efficient data handling.
🚀 Tech Stack
Frontend: React JS
State Management: Redux Toolkit
Data Fetching: Axios
Icons: React Icons
Styling: CSS
⚙️ Installation
Clone the repository:
bash
Copy code
git clone <repo-url>
Install dependencies:
bash
Copy code
npm install
Start the application:
bash
Copy code
npm start
🔗 API Reference
The application fetches data from the QuickSell API, retrieving tasks and user details for a rich Kanban experience.

📂 Component Breakdown
1. DashView
Main dashboard displaying grouped tasks with sorting options.
Accesses state for tasks and user data using Redux useSelector.
Child Components: Renders individual Card components.
2. Card
Reusable component to display individual tasks.
Props: id, title, tag
3. Loading
Spinner component for loading feedback, powered by react-loader-spinner.
🔄 State Management (Redux Toolkit)
This project uses Redux Toolkit for simplified state management:

Reducers: DataReducer and SelectDataReducer handle fetching and managing task data.
Async Actions: fetchAllData and selectData manage asynchronous data loading and state updates.
<kbd>![](https://res.cloudinary.com/anshumxn09/image/upload/v1692799514/test/quickSell_nycbcs.png)</kbd>


