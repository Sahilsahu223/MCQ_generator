## Django Quiz Generator with Gemini API

This project is a Django web application that uses the Google Gemini API (specifically the `gemini-2.0-flash-exp` model) to generate Multiple Choice Questions (MCQs) from user-provided text.  It includes two HTML pages: one for generating questions and another for viewing/downloading previously generated quizzes.

### Features

* **MCQ Generation:** Generates MCQs from text input using the Gemini API.
* **Quiz History:** Stores generated quizzes, allowing users to view and download them.
* **Two Page Interface:**
    * `Questions Generator`:  For submitting text and generating quizzes.
    * `My Quiz`: For viewing and downloading generated quizzes.

### Technical Details

* **Framework:** Django 4.2+
* **API:** Google Gemini API (`gemini-2.0-flash-exp` model)
* **Database:** SQLite (default, can be changed)
* **Frontend:** HTML, CSS
### Prerequisites

1.  **Python:** 3.8 or higher
2.  **Google Cloud Account:** For access to the Gemini API.
