# Django D3 Visualization 
## 1. Overview
A comprehensive sales management system built with Django and D3.js for data visualization. The system allows data entry, storage using the SQLite database, and powerful interactive visualizations with D3.js.

### Features

* Data Management: Upload and manage sales data with a user-friendly interface
* Data Visualization: Interactive charts and graphs powered by D3.js
* Database Schema: Clear visualization of database relationships using schema-viewer
* Responsive Design: Works on desktop and mobile devices
* Production Ready: Deployment to PythonAnywhere

### Tech Stack

* Backend: Django
* Database: SQLite
* Frontend Visualization: D3.js
* Schema Visualization: Django Schema Viewer
* Deployment: PythonAnywhere

### Database Schema
The system is built around the following data model:
![Sales management system model](https://github.com/user-attachments/assets/d687e788-df7c-40e5-b982-5c5c45c421bb)

* sales_customer: Customer information
* sales_segment: Customer segments information
* sales_order: Order data with customer relationships
* sales_product: Product catalog
* sales_category: Product categories
* sales_orderdetail: Line items for orders

## 2. Usage
* Access the main interface to upload CSV data
* Visualize results through the interactive D3.js charts
* Explore different visualization options available in the application

## 3. Deploy Django to Production using PythonAnywhere
You can see a working demo at [here](https://hangnv.pythonanywhere.com/)

![image](https://github.com/user-attachments/assets/860d498e-cc2c-4aee-82ac-57d5460c6624)


## 4. Acknowledgments
* Django community for the amazing framework
* D3.js for powerful visualization capabilities
* PythonAnywhere for simplified Django deployment
