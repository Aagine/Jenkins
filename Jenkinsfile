pipeline {
    agent any

    tools {
        maven 'Maven 3.9.11'   // Must exactly match the name you gave in Jenkins Global Tool Config
    }

    stages {
        stage('Build') {
            steps {
                echo 'Building the project...'
                sh 'mvn clean package'  // for Linux/mac agents
                // bat 'mvn clean package'  // use this if your agent is Windows
            }
        }
    }
}
