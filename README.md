# CSIT-200 Python Programming: Final Project

## Usage Instructions:

These instructions assume the user has a standard installation of the Anaconda distribution of Python, as well as the Anaconda Navigator and Jupyter Notebook installed, as we have been using in class. 

### Python Environment

For the project to work, the following libraries must be installed for Anaconda:

- `flask`
- `json`
- `datetime`
- `matplotlib`
- `os`
- `flask_sqlalchemy`

Typically, all of these libraries are included in the default Anaconda installation except for `flask_sqlalchemy`.

To install flask_sqlalchemy on Windows using the Conda package manager, open the Anaconda Prompt in cmd.exe or Powershell.exe from the Anaconda Navigator or from the Windows search bar, and run the following command: 

```powershell

conda install -c conda-forge flask-sqlalchemy

```

After unzipping the project directory, open the project using Jupyter Notebook. To run begin running the server, simply run the first Python cell.

To visit and interact with the webpage, open a web browser and enter the following IP address:

http://127.0.0.1:5000

This will open a connection to your localhost on port 5000, which is where the Flask server listens for incoming requests. From here, you may interact with the user-facing portion of the site, including links and blog posts. 

To access the "hidden" admin interface, which allows a site owner to add, edit, and delete content on the site, visit the following IP address in your browser: 

http://127.0.0.1:5000/admin

At this point, you should be prompted to enter a password. The default credentials are as follows:

username: `admin`

password: `password`

From here, you may add, edit and delete blog posts. 