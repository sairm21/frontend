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
                sh 'sonar-scanner -Dsonar.host.url=http://172.31.47.19:9000 -Dsonar.login="admin" -Dsonar.password="S@ir&m1221" -Dsonar.projectKey=frontend'
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