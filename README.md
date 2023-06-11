# backend-intern-assignment

1)Flask application that implements a simple task management API using a MySQL database.

2)Flask app is created and a connection to the MySQL database is established using the pymysql library.

3)Task class is defined to represent a task object with properties such as title, description, due date, and status.

4)/tasks route with the POST method is defined to create a new task. The route expects JSON data containing the task details, which are then inserted into the tasks table in the database.

5)/tasks/int:task_id route with the GET method is defined to retrieve a specific task based on its ID. The route queries the database for the task with the given ID and returns its details in JSON format.

6)/tasks/int:task_id route with the PUT method is defined to update an existing task. The route expects JSON data containing the updated task details, which are then used to update the corresponding task in the database.

7)/tasks/int:task_id route with the DELETE method is defined to delete a task with the given ID from the database.

8)/tasks route with the GET method is defined to retrieve a list of all tasks in the database. The route queries the database for all tasks and returns them as a JSON array.

9)replace 'your_mysql_username', 'your_mysql_password', and 'your_database_name'.
