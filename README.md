# sqlrepo
<b>Setting Up MySQL Database Server and Azure Data Studio</b>

Installing MySQL Database Server</b>

<b>1. Download MySQL Server:</b>

- Go to the official MySQL website (https://www.mysql.com/) and download the MySQL Community Server appropriate for your operating system.
  
<b>2. Install MySQL Server:</b>
- Follow the installation instructions provided by MySQL to install the MySQL Community Server on your machine.
- During the installation process, set up a root password for MySQL.
Setting Up Azure Data Studio</b>

<b>3. Download and Install Azure Data Studio:</b>
- Go to the Azure Data Studio website (https://docs.microsoft.com/en-us/sql/azure-data-studio/download) and download Azure Data Studio for your operating system.
- Follow the installation instructions to install Azure Data Studio on your machine.
  
<b>4. Connect to MySQL Server in Azure Data Studio:</b>
- Open Azure Data Studio.
- In the Servers view, click on the "New Connection" button.
- Enter the necessary connection details:
	* Server Name: The hostname or IP address of your MySQL server.
	- Authentication Type: Choose "SQL Login" or "Windows Authentication" depending on your MySQL server configuration.
	- Username and Password: Provide the credentials for your MySQL server.
	- Click "Connect" to establish a connection to the MySQL server.
Setting Up GitHub Repository and Connecting Azure Data Studio
Creating a GitHub Repository

<b>5. Create a New GitHub Repository:</b>
- Go to the GitHub website (https://github.com/) and sign in to your account.
- Click on the "+" icon in the top-right corner and select "New repository".
- Choose a name for your repository, add a description (optional), and configure other settings as needed.
- Click "Create repository" to create the new GitHub repository.

<b>6. Connecting Azure Data Studio to GitHub</b>
- Initialize Git Repository in Azure Data Studio:
-	Open your project in Azure Data Studio.
- In the Source Control view, click on the "Initialize Repository" button.
- Follow the prompts to initialize a Git repository in your project.

<b>7. Add Remote Repository:</b>
- In the Source Control view, click on the ellipsis (...) and select "Publish Repository".
- Choose "Add Remote" and provide the URL of the GitHub repository you created earlier.
- Authenticate with your GitHub account if prompted.
- Installing a Copy of the Employee Database Locally

<b>8. Clone the Employee Database Repository:</b>
- Clone the Employee Database repository from GitHub to your local machine using the clone URL provided by GitHub.
- Open a terminal or command prompt and use the git clone command followed by the clone URL.
<b>9.	Import Employee Database into MySQL Server:</b>
- Use MySQL command-line client or a GUI tool like MySQL Workbench to import the Employee Database into your local MySQL server.
- Execute the SQL script provided with the Employee Database to create the necessary tables and populate them with sample data.
- Now you have successfully installed the MySQL database server, set up Azure Data Studio to connect to a database server, created a GitHub repository, connected Azure Data Studio to GitHub, and installed a copy of the Employee Database locally. You can now work with the database in Azure Data Studio and version control your project using Git and GitHub.
