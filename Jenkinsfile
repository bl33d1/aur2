pipeline {
    agent any // REQUIRED: Tells Jenkins to run on any available agent

    stages {
        stage('Build') {
            steps {
                // Build the project using a shell step
                // Use 'sh' for Linux/macOS or 'bat' for Windows
                // Adjust the command as needed (e.g., 'python setup.py build')
                sh 'python setup.py'
                // If on Windows, you might prefer:
                // bat 'py setup.py build'sf
                // Or if 'python' is directly availabl e:
                // sh 'python setup.py build'
            }
        }
        stage('ME NGA') {
            steps {
                // Build the project using a shell step
                // Use 'sh' for Linux/macOS or 'bat' for Windows
                // Adjust the command as needed (e.g., 'python setup.py build')
                sh 'echo "LUJTA TU NGA"'
                // If on Windows, you might prefer:
                // bat 'py setup.py build'sf
                // Or if 'python' is directly availabl e:
                // sh 'python setup.py build'
            }
        }
    }
}