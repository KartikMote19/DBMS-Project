## Key Features

- **Inventory Management**: Monitor stock levels, product details, and categories. Manage information related to sizes, colors, prices, and more.
- **Sales Transactions**: Record purchase details, including transaction dates and payment methods. Facilitate invoice and receipt generation.
- **Customer Management**: Maintain detailed customer records, including contact information, purchase history, and loyalty rewards.
- **Staff Management**: Track employee data, such as roles, schedules, and performance metrics.
- **Reporting and Analytics**: Generate reports on sales, inventory, and customer activity to aid in business analysis and decision-making.

## Database Design

The system is structured around key tables and relationships:

- **Products**: Contains details about each garment, including product ID, name, category, size, color, price, and stock quantity.
- **Sales**: Logs each transaction, including sale ID, date, customer ID, total amount, and payment method.
- **Customers**: Stores customer information, such as ID, name, contact details, and purchase history.
- **Staff**: Manages employee information, including staff ID, name, position, contact details, and work schedules.
- **Invoices**: Linked to sales transactions, this table generates detailed invoices for each sale.
