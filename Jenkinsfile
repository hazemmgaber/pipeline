pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                echo "Hello $NAME \n The last name is $NAME  " 
                echo "The selected version is $GITpara " 
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
                echo "Hello $NAME \n The last name is $NAME  " 
                echo "The selected version is $GITpara " 
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying in progress ....'
                sh './script.sh $NAME $Okstatus'
            }
        }
    }
}
