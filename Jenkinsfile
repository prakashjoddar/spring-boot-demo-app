pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        
        //  stage('Checkout') {
        //     steps {
        //         // Checkout the code from GitHub
        //         checkout scm
        //     }
        // }

    }
    
    post {
        success {
            // Actions to perform on successful build
            echo 'Build successful!'
        }
        failure {
            // Actions to perform on build failure
            echo 'Build failed!'
        }
    }
}
