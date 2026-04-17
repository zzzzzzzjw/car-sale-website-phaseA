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
car-sale-website-phaseA/
├── README.md                  # Project documentation
├── index.html                 # Homepage 
├── css/                       # Modular CSS stylesheets
│   ├── box_style.css          # 
│   ├── buyer_style.css        # 
│   └── style.css              # 
├── js/                        # JavaScript modules
│   ├── common/                # Shared utilities
│   │   └── main.js            # Global scripts (e.g., mobile menu toggle)
│   └── modules/               # Feature-specific logic
│       ├── validation.js      # Regex validation for forms
│       ├── car.js             # Car data handling
│       └── search.js          # Search filtering logic
├──  seller/                # Seller module
│      ├── register.html
│      ├── add-car.html
│      └── login.html
│──  buyer/                   # Car module
│     ├── search.html
│     └── detail.html
├── images/                    # Static assets
└──

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



