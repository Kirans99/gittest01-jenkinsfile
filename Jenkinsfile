pipeline {
  agent any;
  stages {
    stage ('BUILD') {
      steps { 
        echo "This is build stage"
        sh 'sleep 3'
      }
    }
    
    stage ('TEST') {
      steps { 
        echo "This is test stage"
        sh 'sleep 3'
      }
    }
    
    stage ('DEPLOY') {
      steps { 
        echo "This is deploy stage"
        sh 'sleep 3'
      }
    }    
  }

}

