pipeline {
    agent any
   
    stages {
        stage("cloning") {
            steps {
                echo "cloning"
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
