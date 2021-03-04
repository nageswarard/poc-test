pipeline {
    agent any

    stages {
        stage('Git-checkout') {
            steps {
                echo 'start checkout..'
                git branch: 'main', credentialsId: 'github-p', url: 'https://github.com/nageswarard/poc-test.git'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
