pipeline {
 agent any
    stages {
             stage('Build Docker Image') {
    steps {
            bat 'docker build -t ShubhamBanekar09 .' 
        }
    }
    stage('Run Container') {
        steps {
                bat 'docker run -d -p 8080:80 ShubhamBanekar09' 
                }
        }
    }
}
