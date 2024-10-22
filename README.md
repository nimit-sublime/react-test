# React-Test

## To set up the backend, follow these steps

  1. Create a React application.
  2. Place the provided db.json file at the top level (same level as package.json).
  3. Install JSON Server globally by running the command: npm install -g json-server.
  4. Launch the JSON Server by running the command: json-server --watch db.json.

## Endpoints for CRUD operations

GET: http://localhost:3000/posts
POST: http://localhost:3000/posts
PATCH: http://localhost:3000/posts/{ID}
DELETE: http://localhost:3000/posts/{ID}

## Utilize the provided endpoint to implement the following features

  1. Fetch specific details and present them in a tabular format (the table should be responsive). Utilize a GET request for fetching the details.
  2. Add a button above the table for adding entries. Upon clicking, a modal should appear with input fields for adding entries, ensuring comprehensive validation, and displaying appropriate messages. Utilize a POST request for this operation.
  3. Include a dropdown in the last column of the table with options to edit and delete specific entries.
  4. Use the same modal for updating entries, and utilize a PATCH request for the update process. Validation should be the same.
  5. Enable users to delete entries directly from the table. Utilize a DELETE request for this operation.
  6. Integrate a search input field at the top of the table, enabling users to search by any chosen column.
  7. Implement sorting functionalities for all columns. 

## Additional Features (Optional)

  1. Integrate pagination for the table.
  2. Include an expand/close icon in the first column to reveal or hide detailed information for each row.

## Extra points for

  1. Additional features
  2. Prepare well-written documentationHow we will judge:

## How we will judge

  - The implemented functionalities should be free of bugs.
  - Maintain high code quality throughout the project.
  - Utilize simplified methods wherever possible.
  - Implement proper error handling for all functionalities.
  - You can choose any design framework. For example, React Bootstrap, Tailwind-CSS, MaterialUI, etc.
