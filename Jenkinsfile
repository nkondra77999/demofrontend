
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'OS-Information Building..'
                sh 'cat /etc/os-release'
            
        }
        stage('Test') {
            steps {
                echo 'Checking Disk Space Third updated 03.08.2024..'
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
