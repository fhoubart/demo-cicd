pipeline {
    agent any

    stages {
        stage('Package') {
            steps {
                sh 'mvn package' 
            }
        }
        stage('Publish') {
            steps {
                echo 'TODO Publish..'
            }
        }
        
    }
    
    post {
        always {
            junit '**/surefire-reports/*.xml'
        }

    }

}
