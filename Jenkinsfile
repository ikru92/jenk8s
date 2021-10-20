pipeline {
    agent any
   
    stages {
        stage("init") {
            steps {
                echo "initing"
            }
        }
        stage("build") {
            steps {
                script {
                    echo "building"
                }
            }
        }
        stage("test") {
             steps {
                script {
                    echo "testing"
                }
            }
        }
        stage("deploy") {
             steps {
                script {
                    echo "deploying"
                }
            }
        }
    }   
}
