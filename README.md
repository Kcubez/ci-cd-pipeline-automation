# Python Calculator CI/CD Pipeline with Jenkins

This project demonstrates a CI/CD pipeline using Jenkins for a simple Python calculator application.

## Prerequisites

- Jenkins installed and running
- Git installed
- Python installed

## Setup

1. **Clone the repository**:

    ```bash
    git clone https://github.com/Kcubez/ci-cd-pipeline-automation.git
    cd ci-cd-pipeline-automation
    ```

2. **Set up a virtual environment and install dependencies**:

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    pip install -r requirements.txt
    ```

3. **Run the application**:

    ```bash
    python app.py
    ```

## Jenkins Pipeline

This project uses a Jenkins pipeline defined in the `Jenkinsfile`.

### Pipeline Stages

1. **Clone Repository**: Clones the GitHub repository.
2. **Set Up Environment**: Sets up the Python virtual environment and installs dependencies.
3. **Run Tests**: Runs the tests (if any).
4. **Build**: Placeholder stage for building the application.
5. **Deploy**: Placeholder stage for deploying the application.

### Post Actions

- Archives build artifacts.
- Publishes test results.

## Jenkins Installation on Mac OS

1. **Install Jenkins**:
    ```bash
    brew install jenkins-lts
    ```
2. **Start the Jenkins service**:
    ```bash
    brew services start jenkins-lts
    ```
3. **Access Jenkins**:
   Open your browser and go to `http://localhost:8080`.

## Contributing

Feel free to fork this repository and submit pull requests.

## License

This project is licensed under the MIT License.