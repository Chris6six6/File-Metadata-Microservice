# File Upload Microservice

This project is a microservice API for handling file uploads. It allows you to upload files through a form and receive details about the uploaded file in the response.

## Form Submission

You can submit a form that includes a file upload.

### Form Details

- The form file input field has the name attribute set to `upfile`.

### Example Usage

**Submit a file:**

- Use a form with a file input field named `upfile`.

**Example Request:**

- Submit a file through the form.

**Example Response:**
```json
{
  "filename": "example.txt",
  "type": "text/plain",
  "size": 12345
}
```

## Technologies Used
- Node.js: JavaScript runtime for the server.
- Express: Web framework used to build the HTTP server.
- Multer: Middleware for handling file uploads in Node.js.

## Deploy
[File Metadata Microservice](https://file-metadata-microservice-6riw.onrender.com/)
