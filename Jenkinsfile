pipeline{
    agent any
    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }

       stage('Deploy HTML File') {
            steps {
                sh 'sudo cp -r /home/rizalkalam/.jenkins/workspace/reactpersuratan/* /var/www/testingfothink.my.id/html/'
            }
        }
    }
}
