pipeline {
    agent any
    stages {
    stage ('TEST') {
        agent {label 'customimage'}
        steps {
            sh 'hostname'
        }
    }
        stage ('test1') {
            agent {
            docker { image 'firstimage:1.0.0' }
            }
            steps {
                sh 'echo hi >/home/jenkins/asdfgh'
            }
        }
            
        
    }
}
