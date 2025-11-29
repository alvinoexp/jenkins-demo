pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Build') {
            steps {pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Build') {
            steps {
                echo "Hello from Jenkins + GitHub!"
                sh '''
                    echo "Running on: $(hostname)"
                    git --version || echo "git not found in PATH?"
                    ls -R
                '''
            }
        }
    }
}

                echo "Hello from Jenkins + GitHub!"
                sh '''
                    echo "Running on: $(hostname)"
                    git --version || echo "git not found in PATH?"
                    ls -R
                '''
            }
        }
    }
}
