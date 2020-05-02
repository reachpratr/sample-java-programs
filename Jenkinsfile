pipeline {
    agent any
    stages {
    stage ('TEST') {
        agent {label 'testagent'}
        steps {
            sh 'hostname'
        }
    }
        stage ('test1') {
            agent {
            docker { image '6668785/firstimage:1.0.0' }
            }
            steps {
                sh 'echo hi >/home/jenkins/asdfgh'
            }
        }
            
        
    }
}
