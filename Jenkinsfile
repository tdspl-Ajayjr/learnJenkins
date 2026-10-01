pipeline {
    agent any

    stages {

        stage('Install Dependencies') {
            steps {
                bat 'call pnpm install --frozen-lockfile'
            }
        }

        stage('Build React App') {
            steps {
                bat 'call pnpm build'
            }
        }

        stage('Deploy') {
            steps {
                bat 'call D:\\Practice\\Jenkins\\deploy.bat'
            }
        }
    }
}