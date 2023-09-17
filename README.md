# DCTP Responsive Table
DevCareer Tech Program - Frontend Engineering - Assignment 01

## Assignment Description
Build a well responsive table with 20 records. You're to use just HTML and CSS, and then push your code to github.  
Note: Your table must be responsive across all devices.  
Goodluck.

## Assignment Solution
A responsive table has been achieved with three files (directory structure below):
```
├── assets
│   ├── css
│   │   └── style.css
│   ├── img
│   │   └── DevCareer-Logo.png
└── index.html
```

As requested, the table was created with 5 columns and 20 rows, prefilled with dummy data.  
NB: **Full Name** and **Slack Profile** are actually real data from the first 20 out of 438 members of the dctp-frontend private channel.

To achieve display responsiveness:
- The text contents in each table cell (except `th`) will wrap to the next line to take as little space as possible on mobile.
- Media queries were applied for mobile to allow horizontal scrolling on the container of the table element.

#### External Resources Used
* Google Fonts: Mooli
* Fomantic UI: Table Design
