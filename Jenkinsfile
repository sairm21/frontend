pipeline {

    agent {
        node { label 'Workstation' }
    }


    stages {
        stage('Unit tests') {
            steps {
                echo "unit tests"
             }
        }

        stage('Code Analaysis') {
            steps {
                echo "code analasys"
             }
        }

        stage('Security Scans') {
            steps {
                echo "security scans"
             }
        }

        stage('Publish a Artifact') {
            steps {
                echo "publish artifacts"
             }
        }
    }
}