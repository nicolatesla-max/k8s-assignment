pipeline {
  
  agent any
  
  stages {
    
    stage("build") {
      
      steps {
        echo 'Building the application'
        echo 'Application Deployed'
      }
      
    }
    
    stage("run backend") {
      
      steps {
        echo 'Executing Maven'
        withMaven() {
          sh 'mvn -version'
        }
      }
      
    }
    
    stage("deploy") {
      
      steps {
        echo 'deploying the application'
      }
      
    }
    
    stage("test") {
      
      steps {
        echo 'testing the application'
      }
      
    }
    
  }
  
}
        
