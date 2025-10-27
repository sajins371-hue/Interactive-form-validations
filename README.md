# Interactive Form Validations

This is a simple interactive registration form built using HTML, CSS and JavaScript, demonstrating client-side form validation techniques.

## 📋 Project Overview

The form (accessible [here](https://sajins371-hue.github.io/Interactive-form-validations/)) includes typical fields such as:
- Name  
- Email  
- Password  
- Phone Number  

When the user enters data and clicks **Submit**, validation routines check that the inputs meet required criteria, and give immediate feedback.

## ✅ Features

- Input validation for each field (for example: non-empty, correct email format, password strength, phone number digits)  
- Real-time or on-submit feedback to the user  
- Clear notification of invalid/missing entries  
- Responsive design so form works well on different device sizes  

## 🧰 Technologies Used

- HTML5 for markup  
- CSS3 for styling  
- JavaScript for validation logic (client‐side)  
- optionally: any CSS frameworks or styling enhancements you used  

## 📂 Usage / How to Run

1. Clone or download this repository (or just open the live demo).  
2. If running locally, open `index.html` (or whichever file this is) in a browser.  
3. Enter values in the form fields and click “Submit”.  
4. Observe validation feedback and adjust entries accordingly.

## 🔍 Validation Rules (Examples)

- **Name**: must not be empty  
- **Email**: must match typical email format (e.g., `someone@example.com`)  
- **Password**: must meet minimum criteria (e.g., length, character types)  
- **Phone Number**: digits only, fixed length (e.g., 10 digits)  

*(Adapt the actual rules you implemented in your JavaScript here.)*

## 📝 How to Modify / Extend

- Add new form fields in the HTML, and assign them `id` or `name` attributes.  
- Write corresponding JavaScript validation logic (e.g., using `regex`, or `input.value.trim()`).  
- Enhance style in CSS (e.g., highlight invalid fields, show custom error messages).  
- Add further client-side or server-side validation as necessary for production.

## 👥 Contribution

Feel free to fork this project, submit pull requests, or propose improvements. If you find bugs or have ideas for enhancement (e.g., stronger password rules, better UX, accessibility improvements), you’re welcome to contribute.

## 📄 License

Specify your chosen license (e.g., MIT, Apache, GPL) here.  
Example: This project is released under the MIT License.