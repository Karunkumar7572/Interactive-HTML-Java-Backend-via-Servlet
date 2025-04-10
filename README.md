# Interactive-HTML-Java-Backend-via-Servlet
# Square Calculator Web App

## 🔸 Overview
A simple Java web app where users input a number via an HTML form. The backend Java class calculates its square and displays the result.

## 🔸 Technologies Used
- Java Servlet
- HTML/CSS
- Apache Tomcat
- JDBC (optional)
- Java logic class (non-servlet)

## 🔸 How It Works
1. User enters a number in `index.html`.
2. The `SquareServlet` receives it and passes it to `SquareLogic.java`.
3. The logic class returns the square.
4. Servlet displays the result on the browser.

## 🔸 Setup
1. Create `WEB-INF/classes/logic/SquareLogic.class`
2. Deploy on Tomcat
3. Visit `http://localhost:8080/SquareApp`


