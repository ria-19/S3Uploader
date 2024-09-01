## Streamlined AWS S3 File Uploads with Spring Boot

### Introduction
This Spring Boot project provides a streamlined approach to uploading files to Amazon Simple Storage Service (AWS S3). It leverages the AWS SDK for Java to simplify the integration process and offers a user-friendly interface for file selection and upload.

## Flow
<img width="1062" alt="Screenshot 2019-10-10 at 21 59 38" src="https://user-images.githubusercontent.com/40702606/66606086-491abc00-eba9-11e9-8051-14d4b8eb1ca1.png">

### Prerequisites
* Java 8 or later
* Maven
* An AWS account with S3 access
* AWS credentials configured in your project (e.g., using environment variables or a properties file)

### Getting Started
1. **Clone the Repository:**
   ```bash
   git clone git@github.com:ria-19/S3Uploader.git
   ```
2. **Install Dependencies:**
   ```bash
   cd S3Uploader
   mvn clean install
   ```
3. **Configure AWS Credentials:**
   * **Environment Variables:** Set `AWS_ACCESS_KEY_ID` and `AWS_SECRET_ACCESS_KEY`.
   * **Properties File:** Create an `application.properties` file and add:
     ```properties
     aws.s3.bucket-name=your-bucket-name
     aws.s3.region=your-region
     ```
4. **Run the Application:**
   ```bash
   mvn spring-boot:run
   ```
5. **Access the Application:**
   Open your web browser and navigate to `http://localhost:8080`.

### Usage
1. **Select File:** Choose the file you want to upload.
2. **Upload File:** Click the "Upload" button.
3. **View Status:** The upload progress and status will be displayed.

### Features
* **Easy Integration:** Simplifies the process of integrating AWS S3 into your Spring Boot application.
* **User-Friendly Interface:** Provides a straightforward user interface for file selection and upload.
* **Progress Tracking:** Displays upload progress and status.
* **Error Handling:** Handles potential errors and provides informative messages.
* **Customizable:** Can be easily adapted to your specific requirements.

### Additional Considerations
* **Security:** Ensure proper security measures are in place to protect your AWS credentials and uploaded files.
* **Performance:** Consider optimizing your application for large file uploads or high-traffic scenarios.
* **Cost:** Be aware of AWS S3 pricing and usage limits to manage your costs effectively.

### Contributing
Contributions are welcome! Please feel free to submit pull requests or issues.

