pipeline {
    agent any
    
    stages {
        stage('Print Hello World and Hostname') {
            steps {
                script {
                    echo 'Hello, World'
                    sh 'echo "Hostname: $(hostname)"'
                }
            }
        }
    }
}
