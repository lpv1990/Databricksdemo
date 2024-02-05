pipeline {
    agent any
    stages {
        stage ('Build') {
            steps {
                bat 'echo Hello Build stage'
                //bat 'mkdir C:\\Db-jenkins-tesst'
            }
        }
        stage ('checkout') {
            steps {
                git branch : 'main', credentialid:'e5a4adda-8639-4cd8-9700-2d68d09bc50c',
                url: 'https://github.com/lpv1990/Databricksdemo.git'
            }
        }
        stage ('Deploy') {
            steps {
                bat 'echo hello Deploy stage'
                bat 'C:\\Users\\l.prasanna.velaga\\AppData\\Local\\Programs\\Python\\Python311\\Scripts\\databricks.exe workspace import_dir /demoone /Shared/lakshmiDBdemo'
            }
        }
    }
}



