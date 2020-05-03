pipeline {
    agent any
    stages {
    stage ('TEST') {
        agent {label 'testagent'}
        steps {
            //sh 'echo  "MVN HOME : $MAVEN_HOME" >/SECONDVOLUMEX/asdfguyt'
            sh '(pwd ; ls /home/jenkins >/tmp/asdfg;cat /tmp/asdfg)'
        }
    }
        
            
        
    }
}
