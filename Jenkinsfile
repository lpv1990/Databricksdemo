pipeline {
    agent any
    stages {
        stage ('Build') {
            steps {
                bat 'echo Hello Build stage'
                //bat 'mkdir C:\\Db-jenkins-tesst'
            }
        }
        stage ('Deploy') {
            steps {
                bat 'echo hello Deploy stage'
                bat 'C:\\Users\\l.prasanna.velaga\\AppData\\Local\\Programs\\Python\\Python311\\Scripts\\databricks.exe workspace import_dir https://github.com/lpv1990/Databricksdemo.git /Shared/lakshmiDBdemo'
            }
        }
    }
}



