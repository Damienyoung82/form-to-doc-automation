# form-to-doc-automation

**form-to-doc-automation** is a Google Apps Script project that automates the client intake and documentation process. This script converts Google Form submissions into customized Google Docs, tailored for website design consultations. It helps streamline client onboarding, document generation, and workflow management for web designers and consultants.

## Features

- Automatically generates a Google Doc from Google Form submissions.
- Customizes the Google Doc with placeholders based on client input.
- Provides a structured template for website design consultations.
- Saves time and improves efficiency by eliminating manual document creation.

## Workflow Overview

1. **Google Form Submission:** Collect client details, project requirements, and design preferences through a Google Form.
2. **Google Spreadsheet Integration:** Form responses are stored in a linked Google Spreadsheet.
3. **Google Apps Script Automation:** A script processes the form responses and populates a Google Doc template with the data.
4. **Document Creation:** A customized Google Doc is created with client information and ready for consultation.

## Setup Instructions

1. **Create a Google Form:**
   - Design a Google Form to collect necessary client information such as name, email, business name, project description, etc.
   - Link the form responses to a Google Spreadsheet.

2. **Create a Google Doc Template:**
   - Create a Google Doc with placeholders such as `{{ClientName}}`, `{{BusinessName}}`, `{{Email}}`, etc.
   - Save the Document ID, which will be used in the script.

3. **Google Apps Script:**
   - Open the linked Google Spreadsheet.
   - Click on `Extensions > Apps Script` to open the Apps Script Editor.
   - Copy and paste the `onFormSubmit` function script into the editor.
   - Update the script with your Google Doc Template ID.

4. **Set Up Trigger:**
   - In the Apps Script Editor, click on the clock icon to set up a new trigger.
   - Choose the `onFormSubmit` function and set it to run on "Form Submit" events.

5. **Test the Workflow:**
   - Fill out the Google Form and submit it.
   - Check the Google Drive for a newly created Google Doc with the populated data.

## Example Usage

This project is ideal for:

- Web designers and developers who want to streamline client onboarding.
- Consultants who need to automate document creation based on client input.
- Anyone looking to automate the process of turning form submissions into structured documents.

## Contributing

If you would like to contribute to this project, please create a fork and submit a pull request. All suggestions and improvements are welcome!

## License

This project is licensed under the MIT License. See the `LICENSE` file for more information.

