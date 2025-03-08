pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Use your own GitHub repository URL
                git 'https://github.com/KevinChaves65/git_action_testing.git'
            }
        }

        stage('Print Message') {
            steps {
                echo "Hello, this is Jenkins running for KevinChaves65's repository!"
            }
        }

        stage('Build') {
            steps {
                echo "Building the project..."
                // Add build commands if needed, for example:
                // sh 'javac src/Main.java'
            }
        }

        stage('Test') {
            steps {
                echo "Running tests..."
                // If you have test scripts, you can add:
                // sh './run_tests.sh'
            }
        }

        stage('Deploy') {
            steps {
                echo "Deployment step (if applicable)..."
            }
        }
    }
}
