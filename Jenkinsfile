#!groovy

//myfirstpipeline
//fusk i don`t know what am I doing

properties([disableConcurrentBuilds()])

pipeline{
    agent{
        label'master'
    }
    options{
        buildDiscarder(logRotator(numToKeepStr: '10', artifactNumToKeep: '10'))
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