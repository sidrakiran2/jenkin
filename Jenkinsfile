pipeline {
    agent any
    stages{
        stage('---clean---'){
            steps{
                sh "mvn clean"
            }
        }
        stage('--test--'){
            steps{
                sh "mvn test"
            }
        }
        stage('--pakaage--'){
            steps{
                sh "mvn package"
            }
        }
    }
}
