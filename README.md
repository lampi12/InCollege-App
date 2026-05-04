# InCollege App

InCollege is a command-line social networking application for college students. It was built as a collaborative class project inspired by LinkedIn, with features for student profiles, connections, job postings, inbox messages, and account settings.

## Tech Stack

- Python
- NumPy data files for local persistence
- Pytest test files for selected workflows

## Features

- Create and log in to student accounts
- Search for other students and send connection requests
- Manage profiles, inbox messages, and user settings
- Browse student-oriented links and policy pages
- Create and view job postings
- Run unit tests for login and feature workflows

## Project Structure

```text
main.py                    # Application entry point
f_BeforeLogin.py           # Signup, login, and pre-login workflows
f_AfterLogin.py            # Authenticated user workflows
f_Epic6.py / f_Epic7.py    # Later feature modules
TextFiles/                 # Policy and informational text content
profileFiles/              # Saved user profile data
test_function*.py          # Pytest test files
*.npy                      # Local application data files
```

## Getting Started

1. Clone the repository:

```bash
git clone https://github.com/lampi12/InCollege-App.git
cd InCollege-App
```

2. Create and activate a virtual environment:

```bash
python -m venv .venv
.venv\Scripts\activate
```

3. Install dependencies:

```bash
pip install numpy pytest
```

4. Run the application:

```bash
python main.py
```

5. Run tests:

```bash
pytest
```

## Notes

This project stores sample/runtime data in local `.npy` files. If you want a clean run, back up or remove those data files before starting the app.
