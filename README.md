# Google Form Submission

This project contains an HTML form that submits data to a Google Form. It includes fields for Title, Full Name, Email, Phone Number, Affiliations, Category, and File Upload. The form is styled with CSS and uses JavaScript to handle the submission process.

## Features

- Custom HTML form with various input fields
- Data submission to a Google Form
- Simple and clean CSS styling
- JavaScript for form submission handling

## Form Fields

- **Title**: A dropdown with options (Prof., Dr., Barr., Mr.)
- **Full Name**: A text input for the user's full name
- **Email**: An email input for the user's email address
- **Phone Number**: A tel input for the user's phone number
- **Affiliations**: A text input for the user's affiliations
- **Category**: A dropdown with options (Professional Member, Student Member, Non Student Member, Non Professional Member)
- **File Upload**: A file input for uploading a file

## Usage

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/your-username/google-form-submission.git
    cd google-form-submission
    ```

2. Replace the placeholder `YOUR_FORM_ID` in the JavaScript with your actual Google Form ID:

    ```html
    var googleFormURL = 'https://docs.google.com/forms/d/e/YOUR_FORM_ID/formResponse';
    ```

3. Replace the entry IDs in the HTML `name` attributes with the actual entry IDs from your Google Form:

    ```html
    <select id="title" name="entry.1234567890">...</select>
    <input type="text" id="fullname" name="entry.2345678901" required>
    <input type="email" id="email" name="entry.3456789012" required>
    <input type="tel" id="phone" name="entry.4567890123" required>
    <input type="text" id="affiliations" name="entry.5678901234" required>
    <select id="category" name="entry.6789012345">...</select>
    <input type="file" id="file" name="entry.7890123456">
    ```

4. Open the `index.html` file in your web browser to view and test the form.

## Deployment

To deploy the form using GitHub Pages:

1. Commit and push your changes to the main branch:

    ```bash
    git add .
    git commit -m "Updated form with Google Form IDs"
    git push origin main
    ```

2. Go to the repository on GitHub, click on "Settings", scroll down to the "GitHub Pages" section, and select the branch to deploy (e.g., `main`).

3. Your form will be available at `https://your-username.github.io/google-form-submission/`.

## Contributing

Feel free to submit issues or pull requests if you find any bugs or have suggestions for improvements.

## License

This project is licensed under the MIT License.

---

Replace `your-username` with your actual GitHub username and `YOUR_FORM_ID` with your actual Google Form ID. This `README.md` file provides a clear overview of the project, usage instructions, and deployment steps.
