

# PG Life Web Application

Welcome to the PG Life Web Application repository! This project is designed to help you manage and showcase property details for a PG (Paying Guest) facility. Whether you're a property owner or a user looking for accommodation, this application has got you covered.

## Technologies Used

In building this web application, I've utilized the following technologies:

- **HTML** : This is the markup language used for creating the structure and layout of the web pages.
- **CSS** : I've employed CSS to add beautiful styles and visual appeal to the web pages.
- **PHP** : PHP is the server-side scripting language used to handle the backend functionalities of the application.
- **JavaScript** : I've used JavaScript to implement interactive elements and client-side logic.
- **Bootstrap** : Bootstrap is a CSS framework that I've used to achieve responsive and mobile-first web design.
- **AJAX** : AJAX allows for asynchronous communication with the server, enabling dynamic content updates without page reloads.
- **SQL Database** : The application utilizes an SQL database to store and retrieve property details.

## File Structure

Let me briefly explain the main files and directories in this repository:

- **logout.php** : This file handles the user logout functionality.
- **dashboard.php** : If you log in, this page displays your personalized dashboard with relevant information.
- **css/** : This directory contains CSS files used for styling the web pages.
- **js/** : JavaScript files reside here, responsible for implementing client-side logic.
- **api/** : This directory contains files related to the API functionalities, such as login, signup, and modals.

* **index.php** : This is the main file of the application. When accessed, it displays the list of property details. It interacts with `property_list.php` to retrieve the property data.
* **property_list.php** : This file contains the logic for fetching and displaying the list of property details.
* **property_details.php** : This file handles the display of individual property details.

## Usage

To use the PG Life Web Application on your local machine, please follow these steps:

1. Clone the repository to your desired location using the command: `git clone https://github.com/your-username/pg-life-web-app.git`
2. Set up a local web server, such as Apache, to host the application.
3. Import the SQL database file named `database.sql` into your database management system (e.g., MySQL).
4. Configure the database connection settings within the PHP files of the application (e.g., `index.php`, `property_list.php`, and `property_details.php`).
5. Once everything is set up, you can access the application through your web browser by visiting the URL `http://localhost/pg-life-web-app/index.php`.

## Contributing

I appreciate your interest in contributing to this project! If you'd like to contribute, please follow these guidelines:

1. Fork the repository to create your copy.
2. Create a new branch for your feature or bug fix, such as `feature/your-feature` or `bugfix/your-bug-fix`.
3. Make your modifications and commit them with descriptive commit messages.
4. Push your changes to your forked repository.
5. Finally, submit a pull request, explaining the changes you've made and why they should be merged.

## License

This project is licensed under the MIT License. Feel free to explore the code, adapt it to your own needs, or use it as a reference. For more information, see the [LICENSE]https://github.com/saifcore7/saif-pg-life/blob/main/LICENSE file.

If you have any questions or need further assistance, please don't hesitate to contact me. Happy coding!
