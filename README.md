## Business Problems with AI

Developed an application to intelligently process email order requests and customer inquiries for a fashion store. The system should accurately categorize emails as either product inquiries or order requests and generate appropriate responses using the product catalog information and current stock status.

## Inputs
Google Spreadsheet Document containing:
Products: List of products with fields including product ID, name, category, stock amount, detailed description, and season.
Emails: Sequential list of emails with fields such as email ID, subject, and body.

### Step 1. Classified emails
Classified each email as either a "product inquiry" or an "order request". 

### Step 2. Processing order requests

For each order request, verifying product availability in stock.
If the order can be fulfilled, creating a new order line with the status “created”.
If the order cannot be fulfilled due to insufficient stock, write “out of stock” and include the requested quantity.
Updating stock levels after processing each order.
Recording each product request from the email.

Created response emails based on the order processing results:
If the order is fully processed, inform the customer and provide product details.
If the order cannot be fulfilled or is only partially fulfilled, explain the situation, specify the out-of-stock items, and suggest alternatives or options (e.g., waiting for restock).

### Step 3. Handled product inquiry
 Responded to product inquiries using relevant information from the product catalog.

# OUTPUT
https://docs.google.com/spreadsheets/d/1j6Ca-TIL76CNqeD3tUhQFroj1FLwZwXav5wHJiAPnE0/edit?gid=2006155750#gid=2006155750
