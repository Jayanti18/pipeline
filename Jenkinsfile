pipeline { 
    agent any 
    stages {
        stage('Building State') { 
            steps { 
                sh 'make' 
            }
        }
        stage('Testing stage'){
            steps {
                sh 'make check'
                 
            }
        }
        stage('Deploying stage') {
            steps {
                sh 'make publish'
            }
        }
    }
}
