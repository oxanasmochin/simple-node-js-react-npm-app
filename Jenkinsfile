pipeline {
    agent  any
    tools {nodejs "node"}
       
    stages {
        stage('Build') { 
            steps {
                bat 'npm install' 
            }
        }
        stage('Build production files') { 
            steps {
                bat 'npm run build' 
            }
        }
    stage('Test'){
        steps {
            echo 'Testing..'
        }
    }
    stage('Deploy'){
        steps {
            echo 'Deploying....'
        }
    }
}
}