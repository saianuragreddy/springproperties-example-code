pipeline {
    agent {label 'master'}
    stages {
        //stage('Source') { // Get code 

        //}
        stage('Compile') { // Compile and do unit testing
            steps {
                // run Gradle to execute compile and unit testing
                sh "java --version"
            }
        }
    }
}
