pipeline {
    agent any

    stages {
        stage('Verify Branch') {
            steps {
                sh(script: '$GIT_BRANCH')
            }
        }
    }
}
