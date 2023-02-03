# <pre>                  IT314 - Software Engineering </pre>

#### Name       : Hetav Vakani
#### StudentID  : 202001447

## 1. Identify FRs and NFRs for Library Information System(LIS)
### Functional Requirements
    1. Student,Professor and Employee
        -> Any non-member should be able to browse and search for books online 
        -> Only valid users should be able to issue and return the books(after logging in on the web application)
        -> If the book is already booked by someone,member should be able to make advance booking
        -> After book is returned,user who has advance booked that specific book should be notified
        -> If no other booking requests are received for a specific borrowed book, the user may extend the return date
        -> User should be notified(for e.g. via mail) when the return date is near
        
     2. Library Staff
        ->Can view the day-to-day transaction details(who issued and who returned which book datewise)
        -> Able to retrive list of currently issued and non-issued books
        -> View the list of pending return requests 
        -> View pending issue requests(advance issue requests which were made)
        -> Locating book's location on shelf
        -> View calculation of fine for late return or damaging book 
        
    3. Librarian Login (Admin Login)
        ->Should be able to add new books into the system  
        ->Should be able to delete book from the system,if a specific book is removed from library. 
        
### Non-Functional Requirements
    
    1. Privacy - Credentials of the user should not get leak.
    
    2. Security - The web application can only be accessed through institute LAN.
    
    3. Scalability - The system should be able to handle traffic due to large number of users.
   
    4. Maintainability - The developer should be able to easily update the applicationn even after deployment. 
    
    5. Compatibility - The website should be easily accessible through any basic web browser that supports html5 and should be able to run on mobile phone.
    
    6. Reliability- The database must follow general priciples of transaction and ACID properties
    
    7. Validation - System must validate user at time of issue and return
    
    8. Ease of Usability - The interface of the web application should be easy to use.
    
    9.Performance - The application should be fast and reilable with minimum downtime.
    
    10.Recovery - Should be able to recover lost data in case of failures
    
----
## 2. Identify scope, features and non-functional aspects of the following problem.

### 1. Scope
    -> To develop a mobile application that caters to some of the basic requirements of the community(recognize key sound events of interest to this community) of hearing-impaired people.
    -> The application's target market is those with debilitating hearing loss, which affects 466 million people worldwide, or around 5% of the world's population.
    
### 2. Features
    -> Alert the user about the incoming sounds using AI such as car horns and babies 
    -> To work in real time, the latency should be low
    -> Notify friends and relatives if a major emergency is identified and the user doesn't respond
    -> The application records audio occurrences, giving users access to a history of some of these events. 
    -> Application should have GPS module so that caretakes can detect the location of impaired person.

### 3. Non-Functional aspects
    1. Performance - To guarantee that users receive alerts and logs on time, the application should operate in real-time with minimum latency.
    
    2. Usability - The application should be simple to use and accessible to people who are hard of hearing. This involves creating an interface that is simple to use.
    
    3. Security - The application shall ensure the security and privacy of user data and preserve personal data privacy.
    
    4. Compatibility: The application should be compatible with Android devices, ensuring that users with different devices can use the application.

    5. Reliability: To ensure that users can access the programme whenever they need it, it must be dependable and accessible when required.
    
----
