<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>README - Spring Boot eCommerce</title>
    <style>
        body { font-family: Arial, sans-serif; line-height: 1.6; margin: 20px; }
        h1, h2 { color: #333; }
        code { background: #f4f4f4; padding: 2px 4px; border-radius: 4px; }
        pre { background: #f4f4f4; padding: 10px; border-radius: 4px; overflow-x: auto; }
        ul { padding-left: 20px; }
    </style>
</head>
<body>
    <h1>Spring Boot eCommerce Application</h1>
    <p>A fully functional eCommerce platform built using Spring Boot.</p>
    
    <h2>Features</h2>
    <ul>
        <li>User authentication and authorization</li>
        <li>Product catalog management</li>
        <li>Shopping cart and checkout</li>
        <li>Order processing and tracking</li>
        <li>Admin dashboard for management</li>
    </ul>
    
    <h2>Technologies Used</h2>
    <ul>
        <li>Spring Boot & Spring Security</li>
        <li>Spring Data JPA (Hibernate)</li>
        <li>MySQL Database</li>
        <li>Thymeleaf for UI</li>
        <li>Bootstrap for styling</li>
    </ul>
    
    <h2>Installation</h2>
    <pre><code>git clone https://github.com/your-repo/spring-ecommerce.git

cd spring-ecommerce
mvn clean install</code></pre>
    
    <h2>Running the Application</h2>
    <pre><code>mvn spring-boot:run</code></pre>
    
    <h2>Database Configuration</h2>
    <p>Modify <code>application.properties</code> with your MySQL credentials:</p>
    <pre><code>spring.datasource.url=jdbc:mysql://localhost:3306/ecommerce
spring.datasource.username=root
spring.datasource.password=yourpassword</code></pre>
    
    <h2>API Endpoints</h2>
    <ul>
        <li><code>GET /api/products</code> - Retrieve all products</li>
        <li><code>POST /api/cart</code> - Add item to cart</li>
        <li><code>POST /api/orders</code> - Place an order</li>
    </ul>
    
    <h2>License</h2>
    <p>Distributed under the MIT License. See <code>LICENSE</code> for more details.</p>
</body>
</html>
