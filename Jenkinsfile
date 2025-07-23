pipeline { 
    agent any  
    tools {
        maven 'apache-maven-3.0.1' 
    }
    stages { 
        stage('Build Maven') { 
            steps { 
               echo 'This is a minimal pipeline.' 
               sh 'mvn clean install'
            }
        }
    }
}
