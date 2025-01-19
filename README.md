# Rs_SpringBoot_studentdb

Student Management Application
A robust and user-friendly Spring Boot application designed to manage student registrations and related operations. This project includes various enhancements for better structure, error handling, validation, and user experience.

Key Features:
Backend Enhancements:
  Error Handling: Introduced try-catch blocks and descriptive exception messages for smoother operations.
  Validation: Ensured data integrity with input validations such as non-null, non-negative checks, and regex patterns.
  Null Checks: Prevented failures by checking for null values and verifying the existence of students before update or delete operations.
  Optional Usage: Leveraged Java Optional to handle missing data cleanly.

Frontend Enhancements:
  Course Dropdown: Added a predefined dropdown list for the course selection, ensuring data consistency.
  Responsive UI: Utilized Bootstrap classes for a clean and responsive layout, improving the overall user experience.
  Validation Feedback: Inline error messages with Thymeleaf validation, ensuring immediate feedback for invalid inputs.
  Delete Confirmation: Added JavaScript confirmation to avoid accidental deletions.

Dynamic Features:
  Real-Time Fee Adjustment: The balance fee dynamically updates based on user inputs for paid fees and selected courses.
  Sorting and Filtering: Enhanced sorting and added a "Sort By" dropdown with improved alignment and styling.
  Dynamic Table Updates: Conditionally displayed messages when no students exist and improved table usability with hover effects.

Technologies Used:
  Spring Boot
  Thymeleaf
  Bootstrap
