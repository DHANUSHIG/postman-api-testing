API Testing with Postman

This repository contains API testing collections created using Postman. The purpose is to test student-related APIs for various operations such as GET, POST, PUT, and DELETE And validate the Responses by Writing the Scripts.

Project Structure
├── Student_Api.postman # Postman collection (custom file)
├── Student.json # Sample student data payload

---

Features Covered

- ✔️ Create a new student (POST)
- ✔️ Get student details (GET)
- ✔️ Update student details (PUT)
- ✔️ Delete student record (DELETE)
- ✔️ Validations for invalid inputs
- ✔️ JSON body with headers and authentication 

---

How to Use

1. Open Postman.
2. Click Import → Select Student_Api.postman 
3. Open the Command Prompt in the Desktop and create the remote api
   *navigate to the file (Student.json)  location in the cmd promt
   *Run the cmd prompt (json-server Student.json) to keep the api alive and don't close the cmd prompt
3. Explore the saved requests under Collections.
4. Run requests individually or use **Runner** for automation.

---

Tools Used

Postman for REST API testing
JSON format for payloads and collections
Local environment  setup 

---

Future Improvements

Add Newman for CLI test automation
 Write test cases using Postman tests (JavaScript snippets)
Include environment variables for dynamic URLs

---

Author

**Dhanush I G**  
📧 dhanushdalavayi82@gmail.com  
📍 Bangalore, India

---

 Feel free to fork, clone, or contribute to this repo. Suggestions are always welcome!
