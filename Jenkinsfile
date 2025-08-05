pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the project...'
                // If Maven is installed and configured on Jenkins agent, run:
                sh 'mvn clean package'
            }
        }
    }
}
