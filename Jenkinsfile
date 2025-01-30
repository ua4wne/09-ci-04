pipeline {
    agent {
        label 'ansible'
    }
    stages {
        stage('Sync Git') {
            steps {
                git branch: 'main', url: 'https://github.com/ua4wne/vector-role.git'
            }
        }
        stage('Test'){
            steps{
                sh 'molecule test'
            }
        }
    }
}