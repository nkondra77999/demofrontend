
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sh 'cat /etc/os-release'
            }
        }
        stage('Test') {
            steps {
                echo 'Checking Disk Space how can free..'
                sh 'free -m'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Checking disk space....'
                sh 'df -h'
            }
        }
    }
}
