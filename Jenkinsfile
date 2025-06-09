pipeline {
    agent {
        label "xcode"
    }
    options {
        ansiColor("xterm")
    }
    stages {
        stage("Checkout") {
            steps {
                deleteDir()
                checkout scm
                sh "bundle install"
            }
        }
    }
}