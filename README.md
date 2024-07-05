# Blogify

**Description:**
Blogify is a full-stack application built using React, Node.js, and MySQL. It allows users to write and categorize blogs, providing an organized and user-friendly platform for sharing and discovering content.

**Features:**
- **Blog Creation**: Users can create, edit, and delete their own blog posts. (media upload supported as well)
- **Categorization**: Blog posts can be categorized into various sections such as Science, Art, Technology, and more, making it easy for users to find content that interests them.
- **User Accounts**: Users can create accounts, log in, and manage their profiles.
- **Category Pages**: Dedicated pages for each category to display relevant blog posts.

**Technologies Used:**
- **Frontend**: React
- **Backend**: Node.js
- **Database**: MySQL

Feel free to explore the project, contribute, or provide feedback!

---

### Getting Started

#### Prerequisites

- Node.js
- MySQL
- Yarn

#### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/blogify.git
    ```
2. Navigate to the project directory:
    ```sh
    cd blogify
    ```
3. Install dependencies for the frontend and backend:
    ```sh
    cd client
    yarn install
    cd ../server
    yarn install
    ```
4. Set up the MySQL database:
    - Create a new database and update the database configuration in the server's `.env` file.

5. Start the development server:
    - Start the backend server:
      ```sh
      cd server
      yarn start
      ```
    - Start the frontend development server:
      ```sh
      cd client
      yarn start
      ```

---
