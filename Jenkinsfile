pipeline {
    agent { docker 'maven:3.3.3' }
    stages {
        stage('maven version') {
            steps {
                sh 'mvn --version'
            }
        }
        stage('Build') {
            steps {
              sh 'echo "Hello World"'
              sh '''
                echo "Multiline shell steps works too"
                ls -lah
              '''
          }
        }
    }
}
