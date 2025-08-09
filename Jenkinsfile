pipeline {
    agent any
    triggers {
        cron('H H * * 0') // Runs every Sunday
    }
     /*   stages {
        stage('Checkout') {
            steps {
                // Intentional error: wrong branch name
                checkout([$class: 'GitSCM',
                          branches: [[name: '*/master']], // should be '*/main'
                          userRemoteConfigs: [[url: 'https://github.com/RitaRai/jenkins-pipeline-demo.git']]*/
   //             ])
    //        }
    //    }

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
            }
        }
    }
}