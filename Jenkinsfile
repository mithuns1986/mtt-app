pipeline { 
    agent any  
    stages { 
        stage('Build Maven') { 
            steps { 
               echo 'This is a minimal pipeline.' 
               sh 'mvn clean install'
            }
        }
    }
}
