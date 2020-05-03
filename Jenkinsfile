pipeline {
    agent any
    stages {
    stage ('TEST') {
        agent {label 'customimage'}
        steps {
            sh 'echo  "$MAVEN_HOME" >/home/jenkins/we'
        }
    }
        
            
        
    }
}
