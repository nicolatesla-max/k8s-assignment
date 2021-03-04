pipeline {
  
  agent any
  
  stages {
    
    stage("build") {
      
      steps {
        echo 'Building...'
      }
      
    }
    
    stage("deploy") {
      when {
        expression {
          env.BRANCH_NAME == 'dev'
        }
        
      }
      steps {
        echo 'Deploying...'
      }
      
    }
    
    stage("test") {
      
      steps {
        echo 'Testing...'
      }
      
    }
    
  }
  
}
        
