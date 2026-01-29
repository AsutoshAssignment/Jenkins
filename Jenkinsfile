pipeline { 
    agent any

    stages {
        stage('Clone Git') {
            steps {
                // git branch: 'main',
                    url: 'https://github.com/AsutoshAssignment/Jenkins.git'
            }
        }

        stage('Build Code') {
            steps {
                sh 'chmod +x Prog1.py'
                sh './Prog1.py'
            }
        }

        stage('Test Code') {
            steps {
                sh 'chmod +x Test.py'
                sh './Test.py'
            }
        }
    } 
}
