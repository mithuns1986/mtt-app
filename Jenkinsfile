pipeline { 
    agent any  
    tools {
        maven 'M3' 
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
