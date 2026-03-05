pipeline {
    agent any

    stages {

        stage('Install Dependencies') {
            steps {
                sh 'npm install'
            }
        }

        stage('Build') {
    steps {
        sh 'export NODE_OPTIONS=--openssl-legacy-provider'
        sh 'npm run build'
    }
}
    }
}
