stage('SonarQube analysis') {
    withSonarQubeEnv('SonarQubeServer') {
        sh 'sonar-scanner'
    }
}
