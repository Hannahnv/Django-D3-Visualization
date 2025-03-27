# Django D3 Visualization 
## 1. Overview
Django D3 Visualization is a comprehensive sales management system that leverages Django for backend operations and D3.js for interactive data visualizations. The system enables efficient data entry, storage using a SQLite database, and dynamic charting for insightful business analytics.

### Features
- **Data Management**: Easily upload and manage sales data with an intuitive interface.
- **Interactive Visualizations**: Utilize D3.js to create dynamic charts and graphs for deeper insights.
- **Database Schema Visualization**: Understand database relationships clearly using Django Schema Viewer.
- **Responsive Design**: Ensures seamless user experience across desktop and mobile devices.
- **Production Ready**: Effortless deployment with PythonAnywhere.

### Tech Stack
- **Backend**: Django  
- **Database**: SQLite  
- **Frontend Visualization**: D3.js  
- **Schema Visualization**: Django Schema Viewer  
- **Deployment**: PythonAnywhere  

## 2. Database Schema
The system is structured around the following core data models:
![Sales management system model](https://github.com/user-attachments/assets/d687e788-df7c-40e5-b982-5c5c45c421bb)

- `sales_customer`: Stores customer details.  
- `sales_segment`: Categorizes customer segments.  
- `sales_order`: Manages order records with customer relationships.  
- `sales_product`: Maintains the product catalog.  
- `sales_category`: Organizes products into categories.  
- `sales_orderdetail`: Contains line items for each order.  

## 3. Usage

1. **Upload Sales Data**: Access the web interface to upload CSV files containing sales records.  
2. **Visualize Data**: Explore various interactive D3.js charts representing key sales insights.  

## 4. Deploy Django to Production using PythonAnywhere
To deploy your Django project on PythonAnywhere, follow these steps:

1. Create an account on [PythonAnywhere](https://www.pythonanywhere.com/).  
2. Upload your Django project files.  
3. Set up a virtual environment and install dependencies.  
4. Configure your WSGI settings.  
5. Run migrations and collect static files.  
6. Launch your application and access it online.
   
See the working demo [here](https://hangnv.pythonanywhere.com/)

![image](https://github.com/user-attachments/assets/860d498e-cc2c-4aee-82ac-57d5460c6624)


## 5. Acknowledgments
* **Django community** for the amazing framework
* **D3.js** for powerful visualization capabilities
* **PythonAnywhere** for simplified Django deployment






