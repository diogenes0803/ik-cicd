pipeline {
    agent any
    stages {
        stage("Build") {
            steps {
                nodejs('node18') {
                    sh 'npm install'
                    sh 'npm run build'
                }
            }
        }
        stage("Deploy") {
            steps {
                echo "This is the first step in the Deploy Stage"
            }
        }
    }
}
