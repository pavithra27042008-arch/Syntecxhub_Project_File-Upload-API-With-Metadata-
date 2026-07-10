Syntecxhub Internship Backend Development

Task-2

📁 File Upload API with Metadata

📖 Overview

The **File Upload API with Metadata** is a backend REST API developed using **Node.js**, **Express.js**, and **MongoDB**. It allows users to upload files, store file metadata in a MongoDB database, update or delete uploaded files, and access files through a URL. The API validates file types and file sizes to ensure secure file uploads.

🚀 Features

- Upload files securely
- Store file metadata in MongoDB
- Update uploaded files
- Delete uploaded files
- View uploaded files using a URL
- File type validation
- File size validation
- RESTful API endpoints
- Error handling

🛠️ Tech Stack

Backend
- Node.js
- Express.js

Database
- MongoDB
- Mongoose

Middleware & Packages
- Multer
- dotenv
- cors

API Testing
- Postman

📂 Project Structure

```text
file-upload-api/
│
├── config/
│   └── db.js
│
├── controllers/
│   └── fileController.js
│
├── middleware/
│   └── upload.js
│
├── models/
│   └── File.js
│
├── routes/
│   └── fileRoutes.js
│
├── uploads/
│
├── .env
├── package.json
├── server.js
└── README.md
```

⚙️ Installation

1. Clone the Repository

```bash
git clone https://github.com/your-username/file-upload-api.git
```

2. Navigate to the Project

```bash
cd file-upload-api
```

3. Install Dependencies

```bash
npm install
```

4. Configure Environment Variables

Create a `.env` file:

```env
PORT=5000
MONGODB_URI=mongodb://127.0.0.1:27017/fileupload
```

### 5. Start the Server

```bash
npm start
```

or

```bash
nodemon server.js
```

📌 API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | /api/files/upload | Upload File |
| GET | /api/files | Get All Files |
| GET | /api/files/:id | Get File Details |
| PUT | /api/files/:id | Update File |
| DELETE | /api/files/:id | Delete File |
| GET | /uploads/:filename | View Uploaded File |

📊 File Metadata Stored

- File Name
- Original File Name
- File Type
- File Size
- File Path
- Upload Date

✅ Validation

- Supported File Types:
  - JPG
  - JPEG
  - PNG
  - PDF

- Maximum File Size:
  - 2 MB

📸 Expected Output

- Upload files successfully
- Store file metadata in MongoDB
- Retrieve uploaded file details
- Update uploaded files
- Delete uploaded files
- Access uploaded files through a URL

🔮 Future Enhancements

- JWT Authentication
- Multiple File Upload
- Cloud Storage (Cloudinary/AWS S3)
- File Download API
- Search and Filter Files
- User Authentication & Authorization

👩‍💻 Author

Pavithra Pushpa Lakshmi.K
