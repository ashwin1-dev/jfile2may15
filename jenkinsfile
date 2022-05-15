pipeline {
    agent any
    
    tools {
        maven "jenkin-maven"
           }
    
    stages{
        stage('Scm'){
            steps {
                git 'https://github.com/ashwin1-dev/mvn1.git'
                  }
              }
              
        stage('build') {
            steps {
                sh "mvn clean package"
                 }
              }
              
        stage('deploy') {
            steps {
                sh ' echo "done" '
                }
            }      
        
    }
}
