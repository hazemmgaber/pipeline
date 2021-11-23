pipeline {
    agent any
    environment {
        secret = credentials('jenkins-secret')
    }
    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                echo "Hello $NAME \n The last name is $NAME  " 
                echo "The selected version is " 
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
                echo "Hello $NAME \n The last name is $NAME  " 
                echo "The selected version is " 
            }
        }
        stage('Deploy') {
            steps {
                sh '''
                echo 'Deploying in progress ....' 
                pwd
                '''
            }
        }
        stage('Show the Secrets ') {
            steps {
                sh '''
                echo 'Show the secret  ....' 
                echo  $secret 
                '''
            }
        }
    }
}
