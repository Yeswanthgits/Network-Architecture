![](https://github.com/Yeswanthgits/Network-Architecture/blob/main/3%20Tier%20Architecture/3%20Tier%20Architecture.jpg)

> # 3 Tier Network Architecture:

---

This architecture is slightly similar to the 2 Tier architecture pattern. If you ask where does both of these differ means, the server side is separated into the application layer(the user interface) and Database layer(where the application data is stored) in this architrecture but these both application and database layer is interconnected and serves as one in 2 tier architecture.

The main benifit of using this rather than 2 tier is scaling and optimization of database.

---

3-tier architecture is a fundamental architectural pattern that provides a structured approach for building complex applications, including apps and websites. It divides the application into three distinct layers, each with specific responsibilities

`1. Presentation Layer: `

    It works same as 2 tier architecture(if you are a beginner, refer to this https://github.com/Yeswanthgits/Network-Architecture/blob/main/2%20Tier%20Architecture/README.md )

    This layer is developed using HTML, CSS, Javascript, Next.js, React and many other front end tools. 

    The main responsibilities of this layer is
        +Displaying data to the user.
        +Performs basic data validation.
        +Often handles some client-side logic for enhanced user experience.

---

`2. Application Layer: `

    When the user intertacts with the front-end, the requests goes to backend. This is the main duty of this layer. It fetches the information from the database whiuch the user is requested or required by the user and displays on the frontend part depending upon the decision taken by the technician.

    This layer can be developed using many backend technologies. Some of the popular ones are Python, Java, Javascript, C# and so on.

    The main responsibilities of this layer is
        
        +Handles complex business rules.
        +Manages application workflows.
        +Coordinates interactions between the presentation and data tiers.
        +Often includes security measures to protect sensitive data.

---

`3. Data Tier: `

    The role of this is simple. Storing and managing data in the most and securable way possible and sending it to the `Application layer` as per the queries.

    It can be developed using Relational and Non-Relational Database Management Systems like MySQL, MongoDB, PostgreSql and many more depending upon the use case of the application.

     The main responsibilities of this layer is
        +Provides data storage and retrieval services.
        +Ensures data integrity and consistency.
        +Optimizes data access performance.

If the user base is estimated to increase in the future of the application, then this must be a correct choice to implement in your application architechting process.


In essence, 3-tier architecture provides a structured and scalable foundation for building complex applications. By separating concerns, it improves maintainability, security, and performance.

