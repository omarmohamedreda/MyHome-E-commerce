# MyHome-E-commerce

Welcome to **MyHome-E-commerce**, a comprehensive online platform designed for showcasing and managing e-commerce functionalities. This project demonstrates a robust implementation of an e-commerce application using modern web development practices.

---

## Features

- 🔐 **User Authentication:**
  - Register, login, and secure authentication.
  - User roles for customers and administrators.

- 🛒 **Product Management:**
  - Add, edit, delete, and display products.
  - Categorize products for easy navigation.

- 🛍️ **Cart and Checkout:**
  - Add products to the cart.
  - Proceed to a seamless checkout process.

- 📦 **Order Management:**
  - View order history.
  - Update order statuses for administrators.

- 🔍 **Search and Filtering:**
  - Easily search for products.
  - Filter by categories and price range.

---

## Technologies Used

- 💻 **Frontend:** HTML, CSS, JavaScript
- ⚙️ **Backend:** ASP.NET Core
- 🗄️ **Database:** SQL Server
- 🛠️ **Version Control:** Git & GitHub
- 📚 **Additional Tools:**
  - Entity Framework Core for database interactions.
  - Dependency injection for clean architecture.

---

## Getting Started

### Prerequisites

- 🖥️ Visual Studio 2022 or later
- 🧰 .NET Core SDK 6.0 or later
- 🗃️ SQL Server

### Installation Steps

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/omarmohamedreda/MyHome-E-commerce.git
   ```

2. **Navigate to the Project Directory:**
   ```bash
   cd MyHome-E-commerce
   ```

3. **Setup the Database:**
   - Update the connection string in `appsettings.json` to point to your SQL Server instance.
   - Run the following command to apply migrations and create the database:
     ```bash
     dotnet ef database update
     ```

4. **Run the Application:**
   ```bash
   dotnet run
   ```

5. 🌐 Open your browser and navigate to `https://localhost:5001` (or the specified URL in your development environment).

---

## Project Structure

```plaintext
MyHome-E-commerce/
├── Controllers/       # Handles requests and defines endpoints.
├── Models/            # Contains database models.
├── Views/             # Razor views for UI rendering.
├── wwwroot/           # Static files like CSS, JS, and images.
├── Migrations/        # Entity Framework migration files.
├── appsettings.json   # Configuration file for database and app settings.
└── Program.cs         # Application entry point.
```

---

## Contributions

Contributions are welcome! Please follow these steps:

1. 🍴 Fork the repository.
2. 🌱 Create a new branch.
3. ✨ Make your changes and commit them.
4. 🔄 Submit a pull request.

---

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

---

## Author

Developed by [Omar Mohamed](https://github.com/omarmohamedreda). Feel free to reach out for any questions or feedback!

---

## Acknowledgments

💖 Special thanks to all contributors and resources that made this project possible!
