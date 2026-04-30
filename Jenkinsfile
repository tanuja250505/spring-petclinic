pipeline {
    agent any

    stages {
        stage('git-hub') {
            steps {
            git branch: 'main', url: 'https://github.com/tanuja250505/spring-petclinic.git'
            }
        }
    }
    stage('build generation') {
            steps {
             sh 'mvn package'   
            }
        }
    }
