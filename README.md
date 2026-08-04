# Mini CMS for Document Management

This project is a simple Content Management System (CMS) designed for managing legal documents. It includes an admin panel for a single user to upload, view, and manage documents.

## Project Structure

- **public/**: Contains the front-end files.
  - **index.html**: Main entry point for users.
  - **styles.css**: Styles for the application.
  - **app.js**: Client-side JavaScript for handling interactions.

- **src/**: Contains the server-side files.
  - **server.js**: Entry point for the server, sets up Express and routes.
  - **routes/**: Contains route definitions.
    - **admin.js**: Routes for the admin panel.
    - **documents.js**: Routes for document operations.
  - **controllers/**: Contains the logic for handling requests.
    - **adminController.js**: Manages admin-related actions.
    - **documentController.js**: Manages document-related actions.
  - **models/**: Contains data models.
    - **document.js**: Defines the structure of a document.
  - **middleware/**: Contains middleware functions.
    - **auth.js**: Authentication middleware.
  - **views/**: HTML templates for rendering.
    - **admin.html**: Admin panel template.
    - **login.html**: Login page template.

- **data/**: Contains data files.
  - **documents.json**: Stores document data in JSON format.

- **package.json**: Configuration file for npm, listing dependencies and scripts.

## Setup Instructions

1. **Clone the repository**:
   ```
   git clone <repository-url>
   cd mini-cms
   ```

2. **Install dependencies**:
   ```
   npm install
   ```

3. **Run the server**:
   ```
   node src/server.js
   ```

4. **Access the application**:
   Open your browser and navigate to `http://localhost:3000`.

## Usage

- **Admin Login**: Access the admin panel by navigating to the login page. Use the credentials provided in the project documentation.
- **Manage Documents**: Once logged in, you can upload new documents, view existing documents, and delete documents as needed.

## Contributing

Contributions are welcome! Please submit a pull request or open an issue for any enhancements or bug fixes.

## License

This project is licensed under the MIT License.