pipeline {
    agent any
    stages {
    stage ('TEST') {
        agent {label 'testagent'}
        steps {
            sh 'hostname'
        }
    }
        
    }
}
