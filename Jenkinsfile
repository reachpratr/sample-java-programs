pipeline {
    agent any
    stages {
    stage ('TEST') {
        agent {label 'testagent'}
        steps {
            sh 'echo  "$MAVEN_HOME" >/home/jenkins/we'
        }
    }
        
            
        
    }
}
