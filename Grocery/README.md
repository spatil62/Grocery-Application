# python_projects_grocery_webapp
In this python project, a grocery store management application. It will be 3 tier application,
1. Front end: UI is written in HTML/CSS/Javascript/Bootstrap
2. Backend: Python and Flask
3. Database: mysql

Grocery Store Management System (GSMS)

Overview

Welcome to the Grocery Store Management System (GSMS) – a sophisticated and user-friendly solution designed to revolutionize grocery store operations. GSMS empowers store owners and managers to efficiently handle product inventories, streamline order processing, and gain actionable insights into their business.

Built with Flask and MySQL, GSMS is crafted to provide a seamless and intuitive experience, making store management tasks more straightforward and less time-consuming.

Key Features

Dynamic Product Management:

1)Add & Update Products: Effortlessly manage your inventory by adding new products or updating existing ones.

2)View & Search: Access detailed product information and use search functionality to quickly locate items.

3)Remove Products: Streamline inventory management by removing obsolete products.

Efficient Order Handling:

4)Create Orders: Generate new orders by selecting products and specifying quantities with ease.

5)Track Orders: Monitor order status and details to ensure timely fulfillment and customer satisfaction.

6)Unit of Measurement (UOM) Management:

7)Retrieve UOMs: Access a comprehensive list of measurement units for accurate product handling and sales.
Components

Backend

1)server.py:
Serves as the core of the application, handling API requests and routing.
Manages endpoints for product management, order processing, and UOM retrieval.

2)sql_connection.py:
Establishes and maintains the connection to the MySQL database.

3)ordersdao.py:
Facilitates operations related to order management, including creation, retrieval, and listing.

4)products_dao.py:
Manages product-related functions, including addition, deletion, and retrieval.

5)uom_dao.py:
Handles data related to units of measurement.

Frontend
manage-product.html:
Provides an interactive interface for managing product data. Features include adding new products and viewing existing ones.
order.html:
Offers a streamlined interface for placing and managing orders. Users can add products to orders and view order summaries.

