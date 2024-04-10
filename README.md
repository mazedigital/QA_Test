### Technical Test Assignment for QA Engineer - Product Integrity Position: UI Scenario
#### Task Description
Your task is to develop test cases and automated tests for a web-based “Event Registration Form” used in a conference management application. This form includes several fields and functionalities, each with specific behaviors and requirements:
- **Functionality to Test:**
  1. **Form Fields:**
    - Name (text input)
    - Email (text input)
    - Registration Type (dropdown with options “Attendee”, “Speaker”, “Sponsor”)
    - Number of Tickets (numeric stepper input; visible only when “Attendee” is selected)
    - Presentation Topic (text input; mandatory and visible only when “Speaker” is selected)
    - Agree to Terms and Conditions (checkbox)
    - Submit Button
  2. **Expected Behaviors:**
    - All fields are required unless specified.
    - The form dynamically adjusts to show/hide fields based on the Registration Type selected.
    - The form validates input formats (e.g., Email format).
    - Upon submission, if any validation fails, appropriate error messages should be displayed.
    - A successful submission displays a confirmation message with the details entered.
- **Your Goals:**
  1. **Identify Test Scenarios:** Outline a comprehensive set of test scenarios, including user interactions, form validations, dynamic behavior based on inputs, and both successful and error states.
  2. **Write Detailed Test Cases:** Develop detailed test cases for each scenario identified, specifying:
    - Test Case ID
    - Description
    - Pre-conditions
    - Steps to Execute
    - Expected Result
    - Post-conditions
  3. **Implement Automated Tests:** Utilize a JavaScript-based testing framework suitable for UI testing (e.g., Cypress, Selenium WebDriver with JavaScript bindings) to write automated tests covering the scenarios and test cases you have outlined.
#### Deliverables
1. **Test Case Document:**
  - Document containing the test scenarios and detailed test cases, clearly describing the purpose and expected outcome of each.
2. **Automated Test Code:**
  - Source code for your automated tests, including a README with setup and execution instructions. Ensure your tests are well-commented to explain their purpose and logic.
3.  **Documentation of Expected Failures:**
  - Any observations or notes about test cases that are expected to fail and why, highlighting understanding of potential UI issues or areas for improvement.
4. **Submission Instructions:**
  - Combine your test case document and source code files (including the README) into a single ZIP file.
  - Submit your ZIP file via the email to `eman@maze.digital`.
#### Evaluation Criteria
- **Comprehensiveness of Test Scenarios:** Coverage of various functional and non-functional aspects of the form, including edge cases.
- **Detail and Clarity of Test Cases:** The thoroughness and clarity in the documentation of test cases, highlighting your attention to detail and understanding of potential user interactions.
- **Quality and Effectiveness of Automated Tests:** Your automated tests’ ability to accurately and efficiently validate the UI’s behavior, code quality, and adherence to testing best practices.
- **Documentation and Organization:** The organization of your submission and the clarity of your documentation in both the test cases and code comments/README.
#### Additional Notes
- This assignment does not require you to implement the Event Registration Form itself; your focus should be on testing scenarios and automation.
- Feel free to ask any clarifying questions by reaching out to our recruitment team.
  We’re excited to see your approach to ensuring a flawless user experience through meticulous testing. Good luck with your assignment!

### Instructions for Candidates
- **Objective:** Write automated tests for the Event Registration Form provided in the `index.html` file. Focus on creating tests that interact with the form fields, simulate user inputs, and verify the dynamic behavior and validations of the form.
- **Test Scenarios to Consider:**
  - Form field visibility and requirements change based on the Registration Type selected.
  - Validation messages appear for missing required inputs upon form submission.
  - Successful form submission with all required fields filled correctly.
  - Incorrect email format validation.
  - Conditional fields (Number of Tickets, Presentation Topic) are properly validated when visible.