pipeline {
    agent any
   
    stages {
        stage("init") {
            steps {
                echo "init"
            }
        }
        stage("build") {
            steps {
                script {
                    echo "build"
                }
            }
        }
        stage("test") {
             steps {
                script {
                    echo "test"
                }
            }
        }
        stage("deploy") {
             steps {
                script {
                    echo "deploy"
                }
            }
        }
    }   
}
