### **FileHub - File Sharing Web Application**

**FileHub** is a web-based application for easy and secure file sharing, inspired by ShareIt. This app enables users to upload, share, and download files directly through their browser without requiring external storage or complex setups.

#### **Key Features:**
- **Upload Files**: Easily upload multiple files using a simple form.
- **View and Manage Files**: View uploaded files in a table with options to delete files.
- **Download Files**: Download selected files individually or as a zip archive. Mobile users can download single files at a time.
- **Real-time File Sharing**: Share access to files instantly with a user-friendly interface.
- **Custom IP Instructions**: Provides users with specific IP address instructions for accessing the file sharing service.

#### **Technology Stack:**
- **Front-end**: HTML, CSS, JavaScript
- **Back-end**: PHP
- **Database**: None (Uses file system for storage)
- **File Storage**: Local server storage (in the `uploads` directory)

#### **How to Use:**
1. **Upload Files**:
   - Go to the FileHub page and use the file upload form to select and upload files.
   - Files are stored in the `uploads` directory and become available for sharing and downloading.

2. **View and Manage Files**:
   - The list of uploaded files is displayed in a table.
   - Select files to delete or manage as needed.

3. **Download Files**:
   - Select files to download.
   - On mobile devices, download one file at a time.
   - On desktop devices, download multiple files as a zip archive or individually.

4. **Access Instructions**:
   - For connecting other devices, use the provided IP address and path format shown on the main page.

#### **Installation Instructions:**
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/filehub.git
   ```
2. Navigate to the project directory:
   ```bash
   cd filehub
   ```
3. Ensure the `uploads` directory exists and is writable:
   ```bash
   mkdir uploads
   chmod 755 uploads
   ```
4. Place `index.php`, `upload.php`, `download.php`, and other PHP files in your server's root directory.
5. Access the application via your web browser at `http://localhost/filehub/` or your configured server address.

#### **Contributing:**



Contributions are welcome! Please fork the repository, make your changes, and submit a pull request. Ensure your code adheres to the project's standards and includes relevant documentation.

#### **License:**
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

![image](https://github.com/user-attachments/assets/f2835802-9edb-4097-8951-3407e2896820)

