#!groovy

//myfirstpipeline
//fusk i don`t know what am I doing

properties([disableConcurrentBuilds()])

pipeline{
    agent any
    options{
        buildDiscarder(logRotator(numToKeepStr: '10', artifactNumToKeepStr: '10'))
        timestamps()
    }
    stages {
        stage("First step") {
            steps{
                sh 'echo "Hello World!"'
            }

        }
    }
}
