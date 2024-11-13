## Project View

<kbd>![](https://res.cloudinary.com/anshumxn09/image/upload/v1692799526/test/quickSell2_pjyru9.png)</kbd>

<kbd>![](https://res.cloudinary.com/anshumxn09/image/upload/v1692799514/test/quickSell_nycbcs.png)</kbd>

Kanban Board
A responsive and dynamic Kanban board built with React JS, enabling users to manage tasks effectively. This application features grouping by various criteria (status, user, priority) and implements a loading animation for smooth data loading experience.

Features
Dynamic Grouping: Group tasks by status, user, or priority.
Ordering Options: Sort tasks by title or priority within each group.
Responsive UI: Utilizes React icons and CSS styling for a visually engaging interface.
Loading Spinner: Displays a loading spinner while fetching data from the API.
Redux Integration: State management using Redux Toolkit for efficient handling of tasks and user data.
Tech Stack
Frontend: React JS
State Management: Redux Toolkit
Backend API: Axios for data fetching
Icons: React Icons
CSS: Styled components for a polished UI
Installation
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
API Reference
The application fetches task data from QuickSell API.

Component Breakdown
1. DashView
The main dashboard component that displays grouped tasks with options to sort by title or priority. Utilizes the useSelector hook to access Redux state for tasks and user data.

Props: None
State: Uses Redux selectedData and user from SelectDataReducer.
Child Components: Renders individual Card components for each task.
2. Card
A reusable component to display individual tasks with relevant data such as title and tag.

Props: id, title, tag
3. Loading
Displays a loading spinner using the Circles component from react-loader-spinner.

4. Reducers
DataReducer: Handles task data fetching and storage in state.
SelectDataReducer: Manages selected group data and user status.
Redux Actions
fetchAllData: Fetches data from the API and updates the Redux state.
selectData: Groups tasks based on selected criteria (status, user, priority) and applies optional sorting.
