pipeline {
    agent any

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
                echo 'Deploying in progress ....'  
                pwd
            }
        }
    }
}
