pipeline {
    agent {label 'master'}
    stages {
        stage('Source') { // Get code 
            steps {
                // get code from our Git repository
                git credentialsId: 'github-saberapp-perosnal_access_token_1', url: 'https://github.com/saianuragreddy/springproperties-example-code.git'
            }
        }
        stage('Compile') { // Compile and do unit testing
            steps {
                // run Gradle to execute compile and unit testing
                sh "java --version"
            }
        }
    }
}
