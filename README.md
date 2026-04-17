# car-sale-website-phaseA
QHE4103 Phase A - Online Car Sale Website

Course: QHE4103 Fundamentals of Web Technology
Semester: Semester B - 2026
Institution: Queen Mary School Hainan (BUPT)
Project Phase: Phase A - Front-end Development

# Project Overview
AutoVerve is a responsive website developed by AutoVerve, a car sales company with the same name. The platform enables registered sellers to post vehicle advertisements while allowing buyers to search for desired vehicles based on specific criteria such as model and year. This project utilized pure HTML, CSS, and JavaScript technologies to complete the initial web design and development.

# Key Features
1.The homepage should display the company logo, provide a brief introduction, and include links to other pages.
2.The Seller page must feature. registration, login, and car addition options
3.The login page requires username and password verification.Add car 
4.The car addition page should display vehicle details including color, model, year, location, price, and images.
5.The search page must support comprehensive search functionality.
Registration page: Field validation is required.

# Team members and their respective roles
1. Zhang Jingwen 
    GitHub Username: zzzzzzzjw
    Feature Branch: feature/homepage-search
    Responsibilities: Project setup, Global CSS architecture, Homepage design, PR management, Code review.

2. Li ziyi
    GitHub Username: lzyi06
    Feature Branch: feature/buyer-buyer_style
    Responsibilities: Add Car page, Form handling, Image upload simulation, Search page logic, Car Details page, JS data filtering.


3. Wu Xifei
    GitHub Username: Xifei Wu
    Feature Branch: feature/buyer-buyer_style
    Responsibilities: Seller Registration & Login pages, Regex validation implementation.

# Project Structure
CAR-SALE-WEBSITE-PHASEA/
├── buyer/
│   ├── detail.html
│   └── search.html
├── css/
│   ├── box_style.css
│   ├── buyer_style.css
│   ├── seller_style.css
│   └── style.css
├── images/
│   ├── background.jpg
│   ├── BMW-blue.jpg
│   ├── BMW-white.jpg
│   ├── car1.jpg
│   ├── car2.jpg
│   ├── car3.jpg
│   ├── car4.jpg
│   ├── car5.jpg
│   ├── car6.jpg
│   ├── car7.jpg
│   ├── car8.jpg
│   ├── car9.jpg
│   ├── car10.jpg
│   ├── car11.jpg
│   ├── car12.jpg
│   ├── car13.jpg
│   ├── car14.jpg
│   ├── logo.png
│   ├── sellerpgae-car.jpg
│   ├── SUV-grey.jpg
│   ├── SUV-red.jpg
│   ├── TESLA_S.png
│   └── xiaomi-grey.jpg
├── js/
│   ├── addcar.js
│   ├── judge_login.js
│   ├── register_login.js
│   └── search_function.js
├── seller/
│   ├── add-car.html
│   ├── login.html
│   ├── register.html
│   └── seller.html
├── index.html
└── README.md

# JavaScript Interaction Instructions

All front-end interactions in this project are implemented using native JavaScript without any third-party frameworks. To facilitate learning and demonstration, we utilize the browser's built-in localStorage for temporary data storage, simulating a backend database environment. The following JS files serve specific functions:

1. Register and Login (register_login.js)
Signing Up: When you fill out the registration form, the script stops the page from refreshing, grabs your username and password, and saves them as a simple object in localStorage (under the key autoverve_account). After that, it shows a success message and automatically takes you to the login page.

Logging In: When you try to log in, it checks your input against what's saved locally. If they match, it sets a "logged in" flag and redirects you to the seller dashboard. If not, it tells you the credentials are wrong. If no account exists yet, it politely reminds you to register first.

2. Access Guard (judge_login.js)
This is a simple "gatekeeper" script. It runs on pages that only sellers should see. It just checks if the "logged in" flag is set to true. If you're not logged in, it pops up a warning and sends you straight back to the login page so you can't access restricted areas.

3. Car Search & Display (search_function.js)
Loading Data: When the page opens, it first tries to read car data from localStorage. If it's empty (like the very first time you visit), it loads 6 sample cars and saves them locally so other pages can use them.

Filtering Cars: You can search by model, year, color, or max price. The script compares your inputs with the saved list, updates the page instantly, and shows a friendly message if nothing matches.

Viewing Details: When you click a car card, it attaches the model and year to the URL. The detail page reads that URL, finds the matching car, and automatically fills in the image, price, location, and description.

Recommendations: It also builds a "Recommended Cars" section at the bottom by looping through all available cars and creating clickable cards.

4. Adding Cars & Form Validation (addcar.js)
Real-time Checks: As you type, the script uses simple rules to check if your input is valid. For example, color should only be letters, year must be exactly 4 numbers, and price should only contain digits. If you make a mistake, a red warning appears right below the field.

Submitting the Form: Once everything looks good, it stops the form from refreshing the page, packs your new car into an object, adds it to the car list, and saves it to localStorage. Then it shows a success message and sends you to the search page. If you leave the image field blank, it automatically uses a default placeholder so the layout doesn't break.


# Collaboration Workflow
1. Branching Model:
main: Protected branch, contains only deployable versions.
develop: Integration branch, where features are merged via Pull Requests.
feature/*: Individual branches for each team member's specific task.

2. Development Process:
Each member worked on their own feature branch.
Changes were committed with descriptive messages .
Pull Requests were created to merge features into develop.
At least one other team member reviewed and approved each PR before merging.

# Deliverables
Delivery 1: Non-AI Website Development
Due Date: Friday, 17th April 2026
Submission:
Source Code PDF: Contains all HTML, CSS, and JS files.
Meeting Minute PDF: Weekly records of discussions, progress, and evidence of work.

Delivery 2: GenAI-Powered Development
Due Date: Monday, 27th April 2026
Submission:
Progress Report PDF: Analysis of AI-generated code vs. original code.



