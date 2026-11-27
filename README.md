SmartFood ERP – Packaged Snacks Manufacturing Management System

Project Overview

SmartFood ERP is a web-based Enterprise Resource Planning (ERP) application designed for a South Indian packaged-snacks manufacturing company.

The system integrates sales, billing, production, inventory, dispatch, payments, product costing, and reporting into one platform.

The main objective is to simplify business operations, improve inventory tracking, reduce manual calculations, and provide accurate business reports.

Project Objectives

* Digitize daily business operations.
* Manage retailer orders and sales.
* Generate GST-based invoices.
* Track raw materials and finished products.
* Manage production using Bill of Materials (BOM).
* Monitor stock movements.
* Calculate manufacturing costs.
* Generate reports for management and auditors.

Key Features

1. Sales Management

* Retailer management
* Sales order creation
* Order approval
* Invoice generation
* Sales tracking

2. GST Billing

* GST invoice calculations
* CGST and SGST for intra-state sales
* IGST for inter-state sales
* Invoice PDF generation

3. Production Management

* Production run recording
* BOM-based material consumption
* Production quantity tracking
* Yield variance monitoring

4. Inventory Management

* Raw material stock tracking
* Finished goods inventory
* Stock movement ledger
* Purchase and consumption records
* Closing stock calculations

5. Dispatch Management

* Dispatch recording
* Retailer delivery tracking
* Finished goods stock updates

6. Payment Management

* Payment recording
* Invoice outstanding balance tracking

7. Product Costing

* Raw material costing
* Labour cost calculation
* Utility cost allocation
* Cost per finished packet

8. Auditor Reports

* Inventory reports
* Sales reports
* Production reports
* CSV exports

Technology Stack

Component	Technology
Backend	Python
Framework	FastAPI
Database	SQLite
Frontend	HTML
Styling	CSS
Client-side logic	JavaScript
Deployment	Render

Project Structure

smartfood-erp/
│
├── main.py
├── requirements.txt
├── README.md
├── render.yaml
│
└── static/
    └── index.html

Installation and Setup

Step 1: Clone the repository

git clone https://github.com/kathirp325-bit/smartfood-erp.git

Step 2: Open the project folder

cd smartfood-erp

Step 3: Create a virtual environment

python -m venv venv

Step 4: Activate the environment

Windows:

venv\Scripts\activate

Linux / macOS:

source venv/bin/activate

Step 5: Install dependencies

pip install -r requirements.txt

Step 6: Run the application

uvicorn main:app --reload

Step 7: Open the application

Visit:

http://127.0.0.1:8000

Demo Login Credentials

Role	Username	Password
Administrator	admin	demo123
Owner	owner	demo123
Sales	salesman_a	demo123
Sales	salesman_b	demo123
Production	production	demo123
Auditor	auditor	demo123

Note: These are demonstration credentials. Change them before any public deployment.

Business Use Case

The application represents the operations of a packaged-snacks manufacturing company that purchases raw materials, manufactures snack packets, manages finished goods, sells products to retailers, generates invoices, and tracks payments.

It demonstrates how an integrated ERP system can connect different departments and provide better operational visibility.

Future Enhancements

* Advanced analytics dashboard
* Barcode and QR code integration
* Automated low-stock alerts
* Advanced GST reporting
* Cloud database integration
* Complete audit trail
* Multi-branch management
* Automated backup and recovery

Project Information

Project Name: SmartFood ERP

Project Type: Internship Project

Domain: Enterprise Resource Planning / Manufacturing Management

Application Type: Web Application

Disclaimer

This project is an educational demonstration MVP. It is not certified for production accounting, statutory GST filing, or commercial ERP use. Financial calculations, security controls, and tax compliance should be independently reviewed before real-world use.

Author

Developed as an internship project to demonstrate practical application development and ERP workflow integration.
