pipeline {
  
  agent any
  
  stages {
    
    stage("build") {
      
      steps {
        echo 'Building the application'
        echo 'Application Deployed'
      }
      
    }
    
    stage("deploy") {
      when {
        expression {
          env.BRANCH_NAME == 'dev'
        }
        
      }
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
        
