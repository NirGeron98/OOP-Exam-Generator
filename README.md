# OOP-Exam-Generator
This project was developed as part of an Object-Oriented Programming (OOP) course during my first year of a Bachelor's degree in Computer Science. The main objective was to create an automated system for generating multiple-choice tests. The system includes a question and answer repository, with storage and retrieval functionalities implemented using text files.

Features:

The Question and Answer Management module allows users to perform several critical actions. Users can display all the questions in the system along with their respective answers, with each answer clearly indicating whether it is correct. Adding new answers to existing questions is straightforward, as is the addition of entirely new questions to the repository. Existing questions and answers can be updated effortlessly, ensuring that the content remains current and accurate. Additionally, users can delete specific answers or entire questions along with all associated answers, providing flexibility in maintaining the repository.

The Test Creation module offers both manual and automated options. In manual test creation, users specify the number of questions for the test and select questions from the repository, choosing which answers to include. The system then generates a text file for the test with the selected questions and answers, always including the default options "None of the above" and "More than one of the above." A corresponding answer key file is also generated. For automated test creation, the system randomly selects questions and answers from the repository, ensuring a balanced mix of correct and incorrect answers, and supports the inclusion of open-ended questions.

The File Management system ensures that tests and answer keys are saved as text files with timestamps, facilitating easy organization and retrieval. The question repository is saved and loaded from binary files, eliminating the need for re-entering data with each session.

Each question in the repository is assigned a unique serial number automatically, and questions can be categorized by difficulty level, including easy, medium, and hard. This Question Metadata feature supports both multiple-choice and open-ended questions, adding depth to the test creation process.

Finally, the system includes robust Error Handling capabilities. Custom exceptions are thrown for specific errors, such as attempting to generate a test with too many questions or choosing a multiple-choice question with insufficient answers, ensuring a smooth and error-free user experience.
