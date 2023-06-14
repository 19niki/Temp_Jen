pipeline {
    agent any
    tools { 
      	jdk "JDK11"
    }
    stages {
        stage('Cleanup Workspace') {
            steps {
                echo "Cleaned Up Workspace for "
            }
        }


        stage('Code Build and run') {
            steps {
                 bat 'javac Hello.java'
                 bat 'java Hello'
            }
        }
		}   
}
