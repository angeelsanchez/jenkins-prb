pipeline {
    agent any

    stages {
        stage('Checkout') { 
            steps {
                echo "Dummy Step: Checkout"
            }
        }

        stage('Push to registry') {
            steps {
                echo "Dummy Step: Push to registry"
            }
        }
    } 
    post {
        always {
            echo "Dummy Step: Post Build Action"
        }
    }
}
