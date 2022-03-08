pipeline {
    agent any
    stages {
        stage('Init') {
            steps {
                echo 'Hi, this is Mohan from Mayaitech'
                echo 'We are starting the testing'
            }
        }
        stage('Build') {
            steps {
                echo 'Building Sample Maven Project'
            }
        }
        stage('Deploy') {
            steps {
                echo "Deploying Project In Staging Area"
            }
        }
        stage('Deploy Production') {
            steps {
                echo "Deploying Project In Production Area"
            }
        }
    }
}
