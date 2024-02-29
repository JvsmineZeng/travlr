# CS-465 - Project - Travlr

## Architecture

### Compare and contrast the types of frontend development you used in your full stack project, including Express HTML, JavaScript, and the single-page application (SPA).
> I used the MEAN stack to develop the Travlr flagship website. The customer facing website was developed in Express HTML, which was then converted into a handlebars wireframe to help with load times and backend database communication. Javascript was used to add dynamic modules onto the website, such as a menu, links, and contact forms. Then, MongoDB was used for the database so the page would be able to return an experience tailored to the user. 

### Why did the backend use a NoSQL MongoDB database?
> NoSQL was used since it is scalable and efficient. It can modify the website as needed. It also provides the opportunity to expand the database on a horizontal level.

## Functionality

### How is JSON different from Javascript and how does JSON tie together the frontend and backend development pieces?
> JSON formats Javascript-readable objects. This allows Javascript to easily retrieve and handle blocks of information while remaining compatible with the language. The frontend and backend are tied together by JSON when they communicate with each other when data is at rest, in transit, and in use.

### Provide instances in the full stack process when you refactored code to improve functionality and efficiencies, and name the benefits that come from reusable user interface (UI) components.
> The overhaul of the trip list to trip cards allowed Travlr to manage their trips in a more efficient manner. This allowed the company to create, maintain, or remove trips in “card” objects instead of having to hardcode them into the system. This cuts down on engineering time and costs, and allows the company to “reuse” a template without compromising data.

## Testing

### Methods for request and retrieval necessitate various types of API testing of endpoints, in addition to the difficulties of testing with added layers of security. Explain your understanding of methods, endpoints, and security in a full stack application.
> Utilizing a localhost web allows developers to see if the application is functioning before deploying it to the web. More specifically, it helps verify that the API endpoints are working properly, and if not, what error is thrown. Tools like Postman helps with HTTP requests because it tests securities and endpoints that could protect the system from unauthorized or suspicious requests. Some functions of the full stack include the GET, POST, PUT, and DELETE HTTP requests. They can help maintain the database with functions create, findOne, find, findOneAndUpdate. Endpoints are used to see how data is displayed, and if not, which errors are thrown in the event an error happens. Security allows Travlr to maintain data security and integrity against possible breaches or unauthorized access. This ensures that only Travlr developers and administrators only have this level of access on the website.

## Reflection

### How has this course helped you in reaching your professional goals? What skills have you learned, developed, or mastered in this course to help you become a more marketable candidate in your career field?
>  This course has helped me understand how full stack engineering works. It also helped me understand the process in developing a website, and ways to streamline website development. I also used Postman for the first time in this course, and it was challenging but I was able to get it working. Overall, I felt like this course tested my knowledge and skills acquired from other courses I have taken in the program.
