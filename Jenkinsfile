pipeline {
    agent any
    stages {
        stage('Archive artifact') {
            steps {
               archiveArtifacts artifacts: 'output.txt' fingerprint:true
            }
        }
    }
}
