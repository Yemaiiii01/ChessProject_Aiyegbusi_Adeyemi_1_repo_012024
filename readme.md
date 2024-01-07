# Castle Chess

Castle Chess is a Python program for managing chess tournaments and clubs. This README provides instructions for setting up the project, running the program, and generating linting reports.

## Setup

1. Install required packages:

   ```bash
   pip install flake8 flake8-html
Organize project structure:

bash
Copy code
mkdir -p project_directory/data/clubs
mkdir -p project_directory/data/tournaments
Replace project_directory with the desired directory name.

Linting
To check for linting errors and generate an HTML report, run:

bash
Copy code
python -m flake8 --format=html --htmldir=flake8-report .
Open the generated HTML file in flake8-report to view linting results.