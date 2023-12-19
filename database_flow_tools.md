# Database Diagram (ERD) Design Tool
# dbdiagram.io
<img width="717" alt="image" src="https://github.com/Rockship-Tech/Rockship_wiki/assets/34652279/1b52a4ab-31eb-4b50-8e4d-9c91c5a965d7">

## What is dbdiagram.io?

`dbdiagram.io` is a web-based tool designed for creating and visualizing database schemas effortlessly. It simplifies the process of designing databases by providing an intuitive interface and a simple syntax for defining database structures.

## Key Features

### 1. Intuitive Interface

- User-friendly interface that makes it easy for beginners and professionals alike to design database schemas.

### 2. dbdiagram Language

- Uses a straightforward language called `dbdiagram` for defining database schemas in a human-readable format.

### 3. Collaboration

- Supports collaboration features, allowing multiple users to work on the same database schema simultaneously.

### 4. Export Options

- Provides export options to download diagrams in formats like .png and .svg for use in various documentation and presentations.

### 5. Version Control

- Offers version control capabilities, enabling users to track changes and revert to previous versions if needed.

## How to Use dbdiagram.io

### 1. Accessing the Tool

- Visit [dbdiagram.io](https://dbdiagram.io/) in your web browser to start using the tool.

### 2. Creating a Database Diagram

- Use the `dbdiagram` language to define the structure of your database. For example:

    ```
    Table users {
      id int [pk]
      username varchar
      email varchar
      created_at timestamp
    }
    
    Table posts {
      id int [pk]
      user_id int [ref: > users.id]
      title varchar
      content text
      created_at timestamp
    }
    ```

### 3. Saving and Exporting

- After creating the diagram, use the provided options to save your work and export diagrams in desired formats.

### 4. Collaboration and Version Control

- Utilize collaboration features by inviting team members to work together on the same database schema. Also, take advantage of version control to manage changes efficiently.

## Conclusion

`dbdiagram.io` simplifies the process of database design with its user-friendly interface, `dbdiagram` language, collaboration features, and export options. Whether you are a beginner or an experienced database designer, dbdiagram.io provides a seamless experience for creating and visualizing database schemas.

Start using `dbdiagram.io` today to streamline your database design process!
