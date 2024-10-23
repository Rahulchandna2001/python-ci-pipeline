Python CI Pipeline with GitHub Actions 🚀
This project demonstrates a Continuous Integration (CI) pipeline using GitHub Actions. The pipeline builds and tests a basic Python Flask application, ensuring that new code meets quality standards. Bonus tasks include Docker containerization and Jenkins pipeline implementation.

Project Structure

python-ci-pipeline/
├── app.py              # Flask application
├── requirements.txt    # Dependencies
├── test_app.py         # Unit tests
├── Dockerfile          # Docker configuration
└── .github/
    └── workflows/
        └── ci.yml      # GitHub Actions pipeline
How to Run the Application
Clone the repository:

git clone https://github.com/your-username/python-ci-pipeline.git
cd python-ci-pipeline
Install dependencies:

pip install -r requirements.txt
Run the app:

python app.py
Run the tests:

python test_app.py
CI Pipeline Overview
The GitHub Actions CI pipeline automatically runs when code is pushed or a pull request is opened.

Pipeline Stages:

Build: Install dependencies
Test: Run unit tests and ensure all tests pass
Docker Usage (Bonus)
Pull the Docker image:

docker pull rahulchandna2001/python-ci-pipeline:02
Run the container:

docker run -p 5000:5000 rahulchandna2001/python-ci-pipeline:02