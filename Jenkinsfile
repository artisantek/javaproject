pipeline {
      agent any
      
      stages {
        stage('git checkout') {
        steps {
            git 'https://github.com/testlearnprat/java-example.git'
            }
            }
            stage('build') {
            steps {
            sh 'mvn clean install'
            }
            }
            }
            }