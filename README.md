# workshop management system (WMS)

An application for managing workshop inventory

version: v0.1.0

status: under development

## features

 - Inventory Managment
 - Multi-language support
 - Dark / Light Mode
 - Export to Excel
 - image storage
 - history

## Technologies

 - python
 - CustomTkinter
 - SQLite
 - pillow
 - openpyxl

## structure

```text
workshop-management-system/
│
├── main.py
├── requirements.txt
├── README.md
├── .gitignore
│
├── ui/
│   ├── home.py
│   ├── inventory.py
│   ├── settings.py
│   ├── introduction.py
│   ├── reports.py
│   └── history.py
│
├── database/
│   ├── database.py
│   └── inventory.db
│
├── assets/
│   ├── icons/
│   ├── images/
│   └── logo.png
│
├── exports/
│
│
├── config/
│
│
└── logs/
```

## changelog

see [changelog.md](changelog.md)

## Installation

1.Clone the project
2.Create a virtual environment
3.Install dependencies

pip3 install -r requirements.txt

## roadmap

 - [x] project structure
 - [x] virtual environment
 - [x] requirements.txt file
 - [] application logo
 - [] main menu
 - [] inventory page
 - [] SQlite database
 - [] add parts
 - [] edit parts
 - [] delete parts
 - [] search
 - [] history
 - [] reports
 - [] export excel
 - [] maybe QRcode
 - [] Dark/Light mode
 - [] multi language
 - [] images