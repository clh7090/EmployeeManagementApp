# EmployeeManagementApp

### Frontend Tools and Technologies used
<ul>
<li>React 17.0.2</li>
<li>ES6</li>
<li>NodeJS 16.13.1</li>
<li>Bootstrap 5.1.3</li>
<li>Axios 0.24.0</li>
</ul>

### Backend Tools and Technologies used
<ul>
<li>Springboot 2.6.1</li>
<li>SpringDataJPA</li>
<li>Maven</li>
<li>JDK 1.8</li>
<li>MySQL</li>
</ul>

### Prerequesites 
<ul>
    <li>
    MySQL database connection on port 3306
    </li> <br>
    <li>
    NodeJS version 16.13.1 installed
    </li> 
</ul> <br>

## Setup 
<ol>

<li> <!--- 1 --->
In MySQL, execute the query 'create database employee_management_system;' 
</li> <br>

<li> <!--- 2 --->
    
Configure application.properties by adding the following lines here:
<br> ~/springboot-backend/src/main/resources/application.properties <br>
<br> spring.datasource.url=jdbc:mysql://localhost:3306/employee_management_system?useSSL=false <br>
<br> spring.datasource.username= YOUR_USERNAME <br>
<br>spring.datasource.password= YOUR_PASSWORD<br>

<br>spring.jpa.properties.hibernate.dialect = org.hibernate.dialect.MySQL5InnoDBDialect<br>

<br>spring.jpa.hibernate.ddl-auto=update<br>

</li> <br>

</ol>

## Starting the application
<ol>
<li>
Make sure database is up and running on localhost:3306
</li> <br>

<li>
cd ~/springboot-backend/src/main/java/com/connor <br>
run the SpringbootBackendApplication
</li> <br>

<li>
cd ~/react-frontend <br>
run the command npm install and then npm start to start the website up on localhost:3000
</li> <br>

<li>
You are done! access the website from localhost:3000
</li> <br>
</ol>
