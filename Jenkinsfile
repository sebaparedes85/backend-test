pipeline {
    agent any
    stages {
        stage('Etapa de construccion / build de aplicacion') {
            agent {
                docker {
                    image 'node:22'
                    reuseNode true
                }
            }
            stages{
                stage('Instalacion de dependencias') {
                    steps {                        
                        
                        sh 'ping www.google.com'
                        //sh 'npm install'
                    }
                }
            }
        }
    }
}