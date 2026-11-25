#  LPU Campus Clubs

### Discover Your Community. Explore Your Passion.

A student-focused campus club management website developed as part of the **CSE326 – Internet Programming** course.

The platform provides a common place for students to explore campus clubs, discover upcoming events and workshops, and apply for club memberships.


##  About the Project

University life is not limited to academics. Students also need opportunities to develop practical skills, explore their interests, participate in activities and connect with other students.

**LPU Campus Clubs** aims to make this process easier by bringing club discovery, event exploration and membership registration together on one platform.

The website provides a simple and user-friendly interface for students to discover opportunities beyond the classroom.


##  Key Features

###  1. Interactive Homepage
- Clean and user-friendly interface.
- Navigation between all major website sections.
- Featured campus clubs.
- Upcoming events and workshops.
- Campus statistics and highlights.
- Benefits of joining student clubs.

###  2. Explore Clubs
- Browse available student clubs.
- Search clubs by name and keywords.
- Filter clubs according to categories.
- View club descriptions and activities.
- Explore club information and details.

**Club categories include:**
- Technical
- Cultural
- Sports
- Media
- Entrepreneurship

###  3. Events & Workshops
- Browse campus events and workshops.
- Search events by keywords.
- Filter events by category.
- View event dates, venues and organizers.
- Register for selected events.
- View previously registered events.

###  4. Join a Club
- Student membership registration form.
- Input validation for registration details.
- Preferred club selection.
- Automatic membership ID generation.
- Registration success notification.
- Display previously saved memberships.
- Delete saved demonstration registrations.

###  5. Local Storage
- Saves club membership information in the browser.
- Stores event registration information.
- Maintains saved information after refreshing the page.
- Allows users to view and manage saved demonstration records.

---

##  Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Website structure and content |
| CSS3 | Styling, layouts and responsive design |
| JavaScript | Dynamic functionality and interactivity |
| Browser LocalStorage | Client-side data persistence |
| GitHub Pages | Website hosting and deployment |

**No external frontend framework is required.**

---

##  Project Structure

```text
LPU_campus_Management/
│
├── index.html          # Homepage
├── clubs.html          # Explore Clubs page
├── events.html         # Events page
├── register.html       # Club Registration page
│
├── style.css           # Main stylesheet
│
├── main.js             # Shared JavaScript functionality
├── clubs.js            # Club directory functionality
├── events.js           # Events functionality
├── register.js         # Membership registration
│
├── logo.svg            # Website logo and favicon
│
└── README.md           # Project documentation
```



##  Getting Started

Follow these steps to run the project on your computer.



### 1. Open the Website

Open `index.html` in your browser.

You can also use the **Live Server extension in Visual Studio Code** for local development.

### 2. Explore the Website

Navigate through the following sections:

- Home
- Explore Clubs
- Events
- Join a Club

---

##  Functional Implementation

The project uses JavaScript to provide interactive functionality.

| JavaScript File | Main Responsibilities |
|---|---|
| `main.js` | Navigation, toast notifications and LocalStorage helper functions |
| `clubs.js` | Club data, search, filtering and club details |
| `events.js` | Event data, search, filtering and event registration |
| `register.js` | Membership form validation and registration management |

### Data Storage

The project uses browser LocalStorage with separate storage keys:

- `lpu_club_memberships` – Stores club membership records.
- `lpu_event_registrations` – Stores event registration records.

**Note:** This is a frontend academic demonstration. It does not use a backend server or central database. Saved information remains in the browser where it was entered.

---

##  Project Objectives

- Make campus clubs easier to discover.
- Encourage student participation in extracurricular activities.
- Provide a convenient way to explore campus events.
- Simplify student club membership applications.
- Apply practical HTML, CSS and JavaScript concepts.
- Develop an interactive and user-friendly web application.

---

##  Future Improvements

Some possible enhancements for future development include:

- Student login and authentication.
- Backend integration and database connectivity.
- Centralized membership management.
- Admin dashboard for club coordinators.
- Real-time event updates.
- Email notifications for registrations.
- Integration with official university systems.

---

##  Disclaimer

This website is an academic student demonstration project developed for the CSE326 Internet Programming course.

The club details, event listings and statistics are illustrative demonstration data and should not be treated as official university information.

This is not an official Lovely Professional University website.

---

##  Project Information

**Project Name:** LPU Campus Clubs

**Course:** CSE326 – Internet Programming

**Project Type:** Frontend Web Development

**Technologies:** HTML5, CSS3 and JavaScript

**Hosting:** GitHub Pages

---

##  Acknowledgement

This project was developed as a practical learning experience to understand frontend web development and build an interactive campus-focused web application.

Thank you for visiting **LPU Campus Clubs!**

⭐ If you find this project interesting, feel free to explore the repository.
