Top Courses App

This is a React-based web application that displays a curated list of courses with filtering and liking functionality. The app features a dynamic user interface and integrates several React libraries for enhanced functionality and user experience.

Features

Course Listing: Displays courses with an image, title, and description.

Like Functionality: Allows users to like/unlike courses, with visual feedback using react-icons.

Category Filter: Users can filter courses by categories for easier browsing.

Loading Spinner: Custom spinner displayed while fetching data.

Toast Notifications: Provides real-time feedback on user actions using react-toastify.

Responsive Design: Fully responsive layout built with Tailwind CSS.

Technologies Used

React.js: For building the user interface.

Tailwind CSS: For styling and layout.

React Toastify: For toast notifications.

React Icons: For visually appealing icons.

API Integration: Fetches course data from a backend API.

Installation and Setup

Clone the Repository:

git clone https://github.com/yourusername/top-courses-react.git

Navigate to the Project Directory:

cd top-courses-react

Install Dependencies:

npm install

Start the Development Server:

npm start

The application will be available at http://localhost:3000/.

File Structure

src/:

components/:

Navbar.js: Displays the top navigation bar.

Cards.js: Manages and renders the course cards.

Card.js: Handles individual course card logic and UI.

Filter.js: Renders filter buttons for course categories.

Spinner.js: Displays a loading spinner.

App.js: Main application component.

data.js: Contains API endpoint and filter data.

index.css: Custom styles.

index.js: Entry point for the application.

API Integration

The app fetches course data from the API specified in the data.js file:

export const apiUrl = "<API_ENDPOINT_HERE>";

Replace <API_ENDPOINT_HERE> with your API endpoint if necessary.

Dependencies

Key libraries used in the project:

React.js

Tailwind CSS

React Toastify

React Icons

Install all dependencies with:

npm install

Screenshots

Homepage



Liking a Course



Contribution

Contributions are welcome! If you have suggestions for improving the app or find a bug, feel free to open an issue or create a pull request.

License

This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgments

React Icons for the like/unlike icons.

React Toastify for toast notifications.

Tailwind CSS for the beautiful UI.

Happy coding! If you like this project, don’t forget to star the repository on GitHub!
