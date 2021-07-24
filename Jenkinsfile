pipeline {
    agent { label 'slave-1'} 
    stages {
        stage('checkout') {
            steps {
                sh 'git clone https://github.com/jabedhasan21/java-hello-world-with-maven'
            }
        }
     stage('build') {
            steps {
              sh 'mvn deploy'
            }
        }
      
    }
}
