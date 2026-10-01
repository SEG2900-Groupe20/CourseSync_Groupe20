# CourseSync

> Instantly turn your course syllabi into an organized personal calendar.

CourseSync is a web application that helps students convert their course syllabi (PDF, Word or even a simple photo) into a personal academic calendar. The platform automatically extracts exam dates, assignment deadlines and grade weightings, which eliminates manual schedule entry, reduces deadline anxiety, and ensures students never miss an academic deadline.

## About this repository

This repository contains the **marketing website** of CourseSync, not the application itself.

The goal of the website is to present the product vision and convince other students. It is also a team exercise: it lets every member of the group discover and practice HTML, CSS and JavaScript on a real project.

## The problem

Every term, a student receives several syllabi, each with its own dates, scattered in different places and formats. Copying them by hand takes time, and a single mistake or oversight can mean a missed deadline.

This affects students in general, and those at the **University of Ottawa** in particular, where many courses run at the same time and syllabi are handed out as PDF or Word documents.

## The solution

CourseSync does the work for the student:

1. **Upload** a syllabus (PDF, Word or photo).
2. **Extract** the important dates automatically: exams, assignments, weightings.
3. **Get organized** with one personal calendar, an AI assistant and smart reminders, across all courses.

## Key features (product vision)

- **Smart Syllabus Parsing**: instant extraction of exam dates, assignment deadlines and weightings from PDF files, Word files or simple photos of the document.
- **Personalized AI Academic Assistant**: a dedicated AI agent that learns your study habits, predicts the revision time you need based on course difficulty, and answers your questions about your deadlines ("Do I have assignments due? When are my exams?", "When should I start my web dev project?").
- **Academic Workload Heatmap**: a visual map of risky weeks (green, yellow, red) that automatically calculates how deadlines pile up.
- **Smart Conflict and Overlap Detector**: automatic detection of schedule overlaps and of exams scheduled less than 24 hours apart.
- **One-Click Multi-Calendar Sync**: direct export and automatic sync to Google Calendar, Apple Calendar, Outlook and the .ics format.
- **Dynamic Deadline Reminders**: smart notifications that adapt to the weight of each assessment and to your personal pace.
- **Multilingual Support**: available in 8 languages or more, so every student can use CourseSync in the language they are most comfortable with.

## Why this project

- **Saves time**: no more manual date entry.
- **Less stress**: see at a glance what is coming up and which weeks are at risk.
- **No missed deadlines**: everything lives in one place.
- **A real and immediate need**: every student, including those in our own class, faces this problem. That makes it easy to convince other students like us during the presentations.

## Website pages (suggested)

- **Home**: the promise and a call to action
- **Features**: the seven key features above
- **How it works**: upload, extract, organize
- **Why CourseSync**: the problem for students at uOttawa
- **About** (`pages/about.html`): the team, the mission and the story behind CourseSync
- **Pricing** (`pages/pricing.html`): the plans and what each one includes
- **Terms of Use** (`pages/cgu.html`): the conditions for using the service
- **Privacy Policy** (`pages/privacy.html`): how student data is collected and protected

## Technologies

HTML, CSS and JavaScript only.

## Project structure

```
CourseSync_Groupe20/
├── index.html           home page
├── pages/               one HTML page per section of the website
├── css/                 shared styles + one file per page (css/pages/)
├── js/                  shared code + one file per page (js/pages/)
│   └── utils/           reusable functions
├── assets/              images, icons, fonts
└── docs/                documentation and team conventions
```

Naming rules and teamwork guidelines are in [`docs/CONVENTIONS.md`](docs/CONVENTIONS.md).

## Getting started

1. Clone the repository:

   ```bash
   git clone https://github.com/SEG2900-Groupe20/CourseSync_Groupe20.git
   ```

2. Open `index.html` in a browser.

## Team

Group 20, SEG2900, University of Ottawa.
