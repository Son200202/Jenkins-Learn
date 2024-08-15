pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                checkout scmGit(branches: [[name: 'main']], 
                                userRemoteConfigs: [[url: 'https://github.com/Son200202/Jenkins-Learn.git']])
            }
        }
        stage('Success') {
            steps {
                echo 'Success'
            }
        }
    }
}
