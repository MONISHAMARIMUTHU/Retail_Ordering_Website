My Contribution – Cart Module

Implemented the Cart Management System using Spring Boot, JPA, and MySQL
Features
  1.Create or fetch user cart
  2.Add products to cart (userId, productId, quantity)
  3.Remove items from cart
  4.Clear entire cart
  
Design
Cart → One-to-Many with CartItem
CartItem → Many-to-One with Cart and Product

🔗 APIs
GET /api/cart/{userId} → Get cart
POST /api/cart/add → Add item
DELETE /api/cart/remove/{itemId} → Remove item
DELETE /api/cart/clear/{userId} → Clear cart
