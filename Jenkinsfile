pipeline {
    agent any

    tools {
        // Install the Maven version configured as "M3" and add it to the path.
        maven "mymaven"
    }

    stages {
        stage('Build') {
            steps {
                script {
                // Get some code from a GitHub repository
                 echo "This is a Build Job"
                }
            }
        }
        stage('Test') {
            steps {
                // Get some code from a GitHub repository
                echo "This is a Test Job"
                }
            }
        
        stage('Package') {
            steps {
                // Get some code from a GitHub repository
                echo "This is a Package Job"
                }
            }
    }
}
