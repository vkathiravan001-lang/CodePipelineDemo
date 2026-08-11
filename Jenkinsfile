pipeline {
    agent {
        label 'linux-agent'
    }

    stages {
        stage('Test Agent') {
            steps {
                sh 'hostname'
                sh 'whoami'
                sh 'df -h'
                echo 'Pipeline is running on the Jenkins Agent'
            }
        }
    }
}
