# EventScape: Event Management Social Platform
## FULL STACK APP T3A2-A

## Contributors

**Steph Elsley:** User Stories, Wireframes

**Hannah Scaife:** Data Flow Diagram, App Architechture Diagram

Note: Research and website description completed by both contributors.


## About EventScape

EventScape is a modern, customisable app designed to simplify event planning and invitations. Its offers a private, visually engaging platform where users can host, discover and personalise events with creative themes inspired by Bebo's customisation features. We've integrated the Google Calendar in order to further streamline event scheduling, making it an intuitive alternative to traditional platforms like Facebook Events.

EventScape's focus on privacy, creativity and community engagement makes it ideal for individuals and groups seeking a unique and user-friendly way to organise events, from casual gatherings to larger-scale activites.


## Core Features

1. **Event Creation**:  
   * Add event name, date, time, location, and description.  
   * Pre-set templates and colour schemes for quick customisation.  
   * Options to set events as Public and Private
   * User can track what events they’re attending on the My Calendar page

2. **RSVP and Guest Management**:  
   * Simple RSVP system for attendees, they can pick attending, maybe or cannot attend

3. **Event Discovery**:  
   * Search page to browse public events based on filters (categories, location, date)
  
4. **Privacy and Security**:  
   * Customisable privacy settings for profiles and events
   * Ability to hide personal information

5. **Mobile Optimisation**:  
   * A mobile-first design to ensure smooth event creation and discovery on smartphones.  



## Expanded Features

1. **Advanced Customisation**:  
   * Drag-and-drop editor for deeper event page personalisation.  
   * Upload custom-made images or themes for event invites.  

2. **Google Calendar Integration**:  
   * Sync events to personal calendars using the Google Calendar API.  
   * Receive notifications and reminders directly from the calendar.  

3. **Recurring Events**:  
   * Options to set up weekly, monthly, or custom recurring events.  

4. **Social Sharing**:  
   * Generate shareable links for public events.  
   * Integrated sharing to other platforms (e.g., Instagram, Twitter).  

5. **Community Features**:  
   * Event ratings and reviews to build trust for public events.  
   * User communities or groups for niche interests (e.g., musicians, families).
 




## Target Audience

The app is designed for individuals and small communities seeking a fresh alternative to traditional event platforms like Facebook. 

Key demographics include:  

1. **Young Creatives and Professionals**:  
   - Musicians, artists, designers, and students looking for modern, visually engaging ways to host and find events. This includes personas like Blake and Mia, who value style and ease of use.  

2. **Local Businesses and Event Hosts**:  
   - Bar managers, community leaders, and small business owners who need quick, professional event creation tools. This includes personas like Liam, who regularly host public events.  

3. **Families and Community Organisers**:  
   - Parents, planners, and educators looking for safe, family-friendly event platforms. This includes personas like Sarah, who prioritise privacy and child-appropriate content.  



## Tech Stack

The app is built using the **MERN stack** (MongoDB, Express.js, React, and Node.js) for a scalable, dynamic, and mobile-responsive experience. Additional integrations enhance functionality and user engagement. 

**Frontend:**

* Framework: React
* Routing: React Router DOM
* Styling: Font Awesome, Flexbox
* Build Tool: Vite

**Backend:**

* Framework: Node.js, Express.js
* Database: MongoDB Atlas, managed with Mongoose
* Authentication & Security: bcrypt, jsonwebtoken, helmet

**Third-Party API Integration**

* Google Calendar API, Google's OAuth 2.0 flow.

**Deployment**:

* Front-End: Netlify
* Back-End: Render

**Version Control**:

* Git and GitHub for collaborative development. 

**Development Tools:**

* Build & Development: Vite, Nodemon
* Linting: ESLint with React-specific plugins


## Data Flow Diagram


![DFD](/docs/DFD4.png)


This Data Flow Diagram (DFD) follows the Yourdon and Coad notation in order to provide a clear and structured visualisation of how the data will be processed, stores and communicated within this application. By following this notation style, the diagram ensures consistency, clarity and an easily interpretable view of system interaction at a high level. The diagram uses the following conventions:

* Circles (Processes): Represent the key operations or processes in the system, which transform incoming data into outputs.
* Arrows (Data Flows): Indicate the direction of data movement between processes, data stores and external entites, showcasing how information is passed througout the system. Each arrow is colour-coded, to avoid confusion: a diagram colour key has been included for the same purpose. For further clarity, each arrow has been numbered regarding where each data process begins and ends.
* Squares (External Entities): Depict the external actors or systems that interact with the system, either providing input or receiving input.
* Open Rectangles (Data Stores): Illustrate where data is stored within the system, such as databases or file storage.


## Application Architechture Diagram


![AAD](/docs/APP_ARCH_D.png)



## User Stories

The image below is the first iteration of user stories, giving 4 different perscpectives of what problem the app will solve.

![UserStories](/docs/User%20persona%20version%201.png)

The second iteration(below), is a refined version of the user stories with more of a focus on the MVP of the app.

![UserStories2](/docs/User%20Personas%20Version%202%20.png)




## Wireframes

Sitemap 
<img width="884" alt="Sitemap" src="https://github.com/user-attachments/assets/fc70f7ea-235c-4559-85d8-e6df66485b66">

### Desktop Wireframes

![WireframeDesktop1](/docs/Widescreen%20Wireframes%201.png)

![WireframeDesktop2](/docs/Widescreen%20Wireframes%202.png)

### Mobile Wireframes

![WireframesMobile](/docs/Phone%20Wireframes.png)



## Trello Board

![appdec](/docs/trello/appdesc_checklist.png)

![overview](/docs/trello/overview_trello1.png)

![wireframe](/docs/trello/wireframes_trello.png)



## REFERENCES


S, Y. (2021). _What exactly a MERN stack is?_ [online] Medium. Available at: https://medium.com/techiepedia/what-exactly-a-mern-stack-is-60c304bffbe4.

Visual Paradigm. (2024). _DFD Tutorial: Yourdon Notation._ [online] Available at: https://online.visual-paradigm.com/knowledge/software-design/dfd-tutorial-yourdon-notation.
