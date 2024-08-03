
![](https://github.com/Yeswanthgits/Network-Architecture/blob/main/2%20Tier%20Architecture/2%20Tier.png)

> # Two Tier Network Architecture:

This architecture follows a straightforward approach in solving and creating a website or application.It has only two components.

1. SERVER SIDE COMPONENT
2. CLIENT SIDE COMPONENT

`1. SERVER SIDE`

---

        It handles the backend of the application like bussiness rules, interactions with the database.

        Database contains and stores the application data and manages it for the application.

        Server Side has the most complex bussiness logic and provides services to the client tier.


`2. CLIENT SIDE`

---
        
        This is the section where we as users interact with the application just like you are seeing this page in your browser.

        It has the ability to engage users with the content of the website or application. 

        It collects the user data and sends it to the server side of the application(it handles the rest of the things like user
        authentication and authorization.)
        
        ## Key Roles:

            It's easy to understand and implement, making it easy for small to medium sized applications.

            It typically requires fewer resources and it serves as a base to transitioning to a 3-Tier or higher complex architecture 
            strategies.

In this architecture, scaling of an application plays a major role because it cannot handle higher loads, means when the user traffic exceeds a certain limit, the app cannot withstand that load and crashes. So, one should decide whether they then can choose this or move on with the other available architecture plans.

In summary, while 2-tier architecture is a solid foundation for many applications, its suitability depends on the specific requirements of the project. As the application grows, considering a more scalable and secure architecture like 3-tier or microservices might be necessary.
