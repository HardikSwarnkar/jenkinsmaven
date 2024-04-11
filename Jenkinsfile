pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                // Use Maven to build the application
                bat 'mvn clean package -DskipTests=true'
            }
        }
        stage('Test') {
            steps {
                // Execute tests
                bat 'mvn clean test'
            }
         
        }
        stage('Deployment') {
            steps {
                // Deploy the application
                // Replace with actual deployment script
                echo 'Deployment execution completed'
            }
        }
        stage('Clean Up') {
            steps {
                // Clean up temporary files or resources
                // Replace with actual cleanup script
                echo 'Pipeline execution completed'
            }
        }
    }
}
