# Servlet Cookie Session Management Project 
This is a simple Java web application demonstrating session management using cookies in Servlets. The project allows users to log in, tracks their session using cookies, and provides a logout functionality.
Project Structure

The project has the following structure:
## ServletCookieExample
•	web.xml: Deployment descriptor for the web application.
•	Web Content
•	login.html: Welcome page for the application with a simple login form.
•	LoginSuccess.jsp: Success page displayed upon successful login, showing the username and providing a logout option.
## src
•	com.journaldev.servlet.session
•	LoginServlet.java: Servlet handling the login logic and setting a session cookie.
•	LogoutServlet.java: Servlet handling the logout logic by removing the session cookie.
## Usage
1.	Access the application by opening login.html in a web browser.
2.	Enter the predefined username and password (as coded in LoginServlet).
3.	Upon successful login, you will be redirected to LoginSuccess.jsp showing a welcome message and a logout option.
4.	Clicking the logout button will remove the session cookie and redirect you to the login page.

