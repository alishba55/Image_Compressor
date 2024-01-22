# Image Compressor

## Overview

The Image Compressor project is a Java-based application designed to compress PNG images efficiently. The project includes features such as user registration, login, and a user-friendly interface for uploading, compressing, and downloading images. It leverages the Swing library for GUI components and interacts with a MySQL database for user authentication and registration.

## Features

1. **User Registration and Authentication:**
   - Users can register with a unique username, email, and password.
   - Existing users can log in to access the image compression functionality.

2. **Image Compression:**
   - Users can upload PNG images for compression.
   - The application provides an option to set custom dimensions for the compressed image.

3. **Graphical User Interface (GUI):**
   - The project utilizes Java Swing for a clean and intuitive user interface.
   - Different panels are created for user registration, login, image compression, and result display.

4. **Local Database Interaction:**
   - The application interacts with a local MySQL database for user authentication and registration.
   - Database queries are implemented to check for existing usernames and emails.

## How to Run

1. **Set Up Database:**
   - Ensure you have a local MySQL database set up with the name "ImageCompressorDatabase."
   - Modify the database connection details in the `ImageCompressorDatabase` class if needed.

2. **Compile and Run:**
   - Compile and run the project using an integrated development environment (IDE) like NetBeans or from the command line.
   - Execute the `RegistrationForm` class to launch the registration and login interface.
   - After logging in, the user can use the image compression functionality in the `ImageCompress` class.

3. **Dependencies:**
   - The project uses the MySQL Connector/J library for database connectivity.
   - The [Thumbnailator](https://github.com/coobird/thumbnailator) library is used for image compression.

## Example Usage

1. Register a new user using the registration interface.
2. Log in with the registered credentials.
3. Upload a PNG image using the "Upload Image" button.
4. Set custom dimensions for the compressed image and click "Set Dimensions."
5. View the original and compressed images side by side.
6. Download the compressed image using the "Download Compressed Image" button.

## Notes

- The project includes comprehensive error handling and validation for user inputs.
- Make sure to have the necessary MySQL and Java libraries in the project classpath.

Feel free to explore and contribute to the project!
