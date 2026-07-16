Key: 
Red = optional 
Blue = necessary 
Ski Resort - Project Criteria: 
Project Overview 

I intend to design and develop a comprehensive ski resort management system for a winter resort business. The system will manage customers, accommodation, memberships, reservations, ski facilities, parking, and resort services through an interactive user interface. 

Stakeholders: 

The main group to benefit from the new system will be adults intending to plan a holiday at my resort. They will be able to utilize the system to rent skiing equipment, reserve services such as the ski slopes themselves, or book a room at the resorts many hotels, decreasing or increasing in price depending on distance from the resort, room size, and room attributes. This system improves operational efficiency while offering customers a straightforward and convenient process for planning and managing their stay at the resort. 

Staff at the resort will also benefit from the new system, as the system will cause reduction in staffs' workload, and therefore, increasing efficiency with better time allocation on tasks which may need more resources to complete, such as inventory, and management of systems which need constant updating to function adequately, such as ski slope traffic, equipment renting, and more 

With this system in place, it also means a reduction in staff, reducing OPEX (operating expenses) 

Time/ Hardware constraints: 

My project is constrained by the available development time, due to variables such as other a-level subjects, as well as exams. The project will be developed using Python on a standard computer, limiting complexity of graphics and process-intensive features. As I am still developing my programming skills on more advanced concepts the project will focus more on core functionality such as managing customers, ski slope passes, accommodation availability, package plans, and [INSERT] rather than implementing advanced features such as online payments, simulation of car park space management (if time is scarce) or live weather integration. The project will also use sample data as access to real ski resort databases is unavailable. 

( )Core Features: 

Customer Membership System 

Customers can register and sign up for a membership account. 

Allowing for the customers to save their data, means that they dont have to keep reapplying for certain benefits or plans when booking again or renewing/changing their plan 

Why each feature is necessary 

Possible Extensions 

Tiered memberships (Silver, Gold, Platinum) 

Automatic discount calculations 

Why each feature is necessary 

Members earn loyalty points from purchases and bookings. 

Increases likelihood of customer loyalty to the branch 

Points can be redeemed for discounts on resort services. 

Different membership benefits may apply depending on customer activity or package type. 

Example of OOP 

 

 

Equipment Rental System 

Customers can rent skiing equipment such as: 

Ski poles 

Skis 

Helmets 

Utilising a clock system, with constant checks every iteration; utilises iterative techniques such as while loops 

As well as for loops utilising the previous clock system for the rental function (using time.sleep, I am able to simulate time in a for loops, so i would be able to make durations, which can be used to simulate duration of occupancy to a customer 

Rental availability updates dynamically. 

Real time updates reduce risk of over renting equipment; renting equipment which is not available 

(Optional) determining the price variations: 

Rental pricing may vary based on duration of usage, equipment difficulty: 

In terms of customer safety, increasing prices on more specialist equipment may discourage its usage to customers who may not be familiar with it, ensuring people who are familiar and comfortable with using specialist equipment are able to use it (improves the traffic of the system passively 

 

Object-Oriented Programming Features: 

 Ski Slope Management 

Use Object-Oriented Programming principles to represent different ski slopes. 

Requirements 

Different slopes have different: 

Difficulty levels 

Capacities 

Prices 

Customers can view slope information. 

Customers can see how busy a slope is in real time. 

Why each feature is necessary 

OOP Concepts 

Classes- 

Inheritance- slopes, accommodation 

Encapsulation- customer 

Polymorphism-customer  

 

/\ Accommodation Search System 

Create an accommodation management system using OOP, polymorphism 

Customers should be able to: 

Search accommodation using filters such as: 

Number of beds 

View availability 

Shower/bathroom facilities 

Distance from slopes 

Sort accommodation by: 

Price 

Distance 

Rating/features 

Why each feature is necessary 

Additional Logic 

Resort-owned accommodation becomes cheaper the further it is from the main ski area. 

Discounts apply when staying within the Musa resort branch. 

 

Reservation & Availability Systems: 

Accommodation Occupancy Simulation - queues 

Simulate rooms becoming occupied or vacant. 

Staff and customers can view live room availability. 

The system outputs: 

Available rooms (OOP,polymorphism,queues)– will allow staff and customers to view which rooms are available (use of queues and popping to leave only the available rooms) 

Reserved rooms - will allow staff to see who has reserved the room and for how long and customers to view which rooms are reserved and for how long  

Occupied rooms - will allow staff to see the occupants, and customers to see how long the room will be occupied(for online planning) 

 

Parking Reservation System 

Customers can reserve parking spaces. 

Parking can be booked up to 3 days before a reservation begins. 

Parking spaces use colour-coded sections, as a passive wayfinding system, as well as a systematic way to record spot usage: -   OOP, polymorphism 

Red 

Green 

Blue 

Yellow 

Purple 

Orange 

Why each feature is necessary – this colour coded system adds structure to the system; customers may hopefully find it easier to find their cars; faster access speeds mean less usage time, allowing more customers to utilise the car park 

 An example of this type of system in use at bluwater, used to improve wayfinding therefore 

Additional Features 

Track occupied and available parking spaces 

Link parking reservations to customer bookings 

Why each feature is necessary 

 

[:] Resort Packages & Services: 

Modular Resort Plans 

Customers can choose different resort packages. 

Example Plans 

All Inclusive Plan 

Leisure Plan ( other facilities such as gym/spa 

Nourriture (Food) Plan 

Why each feature is necessary 

Package Benefits 

Packages may include: 

Breakfast 

VIP lounge access 

Spa access 

Bar access 

Equipment discounts 

Why each feature is necessary 

Modular System 

Plans are modular, meaning customers can customise or combine services. 

 

£-Business & Pricing Logic: 

Resort Pricing System 

Prices vary depending on: 

Distance from the ski slopes 

Accommodation type 

Membership status 

Package selected 

Why each feature is necessary 

 

CHECK YOUR PLAN AND ADD OR REDUCE MODULES TO YOUR PLAN           

 

Gondola Monitoring System 

Live tracking of gondola usage/capacity. 

Customers can view how busy gondolas are in real time. 

Why each feature is necessary 

 

[] Database Requirements: 

Relational Database 

The system should use multiple related database tables. 

Possible Tables include: 

Customers 

Memberships 

Reservations 

Accommodation 

Slopes       -  

Parking      - red, green blue, orange purple 

Packages – norriture/food package, spa package etc. 

Payments 

Why each feature is necessary 

Relationships 

One-to-many 

Many-to-many 

Foreign keys 

 

@# Searching, Filtering & Sorting: 

Search Tools 

Users should be able to: 

Filter data based on attributes 

Sort results dynamically 

Search across multiple categories 

Why each feature is necessary 

Examples 

Accommodation filters 

Slope difficulty filters 

Price sorting 

Availability sorting 

 

£ Payment System: 

Payment Validation/Sanitisation 

Implement a payment system with card validation. 

Requirements 

Use the Luhn Algorithm (checksum) to verify payment card numbers. 

Prevent invalid card details from being processed. 

Possible Extension 

Use an API or test payment card dataset for validation/testing purposes. 

 

User Interface: 

Create an intuitive interface for both customers and staff. 

Customer Features 

Booking: 

Accommodation 

Renting equipment   

Reserving parking   

plans/packages 

Viewing slope activity 

Managing memberships 

Why each feature is necessary 

Staff Features 

Monitoring occupancy 

Viewing reservations 

Managing slope capacities 

Updating accommodation availability 

Why each feature is necessary 

 

Research & Evidence/ analysis: 

Research Section 

Include evidence and research for: 

Existing ski resort systems 

Difficulty of slopes which can affect price for customer 

Reservation systems 

Membership systems 

Payment validation methods 

Database design 

User interface design principles 

Why each feature is necessary 

Suggested Research Areas (from el gpt) 

Real-world ski resort booking systems 

Hotel management systems 

Queue/capacity monitoring systems 

Card validation algorithms 

 

This project demonstrates: 

Object-Oriented Programming - polymorphism 

Algorithms 

Searching and sorting 

Relational databases 

Simulations – random and while loops 

Real-time availability systems 

Validation 

Modular design 

Creation of a friendly UI 

Why each feature is necessary 

 

 

Taking existing systems into consideration 

Take into consideration real life statistics when simulating rental return systems and accommodation systems. 

Resort in the alps example: 

Membership/reward system, increasing likelihood of loyalty to the resort/branch 

 

Filter system(merge sort): 

 

 

 

 

 

 

 

 

Establishing layout for the application: 

Main classes: 

Customer: 

Booking: 

 

 

 Staff: 

System traffic: 

inventory 

Accommodation: 

 SkiSlope: 

 Equipment: 

 Rental  Package 

 Reservation 

 Payment System 

 membership 

 

 

Testing 

Variables 

Normal 

invalid 

Boundary 

erroneous 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 
