#!groovy

//homework2

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
                    sh 'docker run hello-world'
            }

        }
    }
}
