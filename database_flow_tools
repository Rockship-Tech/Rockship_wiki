# Introduction to dbdiagram.io

dbdiagram.io is a user-friendly online tool designed for creating and visualizing database schemas effortlessly. With its intuitive interface and simple syntax, it enables developers and database architects to design, document, and collaborate on database structures seamlessly.

## Key Features

### 1. Visual Database Design
- **Drag-and-Drop Interface:** Easily create tables, define relationships, and arrange entities through a user-friendly drag-and-drop interface.
- **Visualization:** Generate visual representations of your database schema instantly to better understand the structure.

### 2. Simple Syntax
- **Easy-to-Understand DSL (Domain-Specific Language):** Utilize a straightforward syntax to define tables, columns, primary and foreign keys, indexes, and relationships.

### 3. Collaboration and Export
- **Team Collaboration:** Share and collaborate on database designs with team members by granting access via URLs.
- **Export Options:** Export schemas as images or SQL code to integrate seamlessly into your development workflow.

## Getting Started

### Syntax Example

The following is an example of the dbdiagram.io syntax:

```sql
// Define tables
Table users {
  id int [pk, increment]
  username varchar
  email varchar [unique]
  created_at datetime
}

Table posts {
  id int [pk, increment]
  user_id int [ref: > users.id]
  title varchar
  content text
  created_at datetime
}

// Define relationships
Ref: posts.user_id > users.id
