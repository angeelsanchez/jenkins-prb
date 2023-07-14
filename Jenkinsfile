pipeline {
    agent {label any}

    stages {
        stage('Checkout') { 
            steps {
                   echo "Dummy Step: push validated image to registry"
        }
        }

        stage('Push to registry') {
            steps {
                echo "Dummy Step: push validated image to registry"
            }
        }
    } 
    post {
        always {
            echo "Dummy Step: push validated image to registry"
        }
    }
}