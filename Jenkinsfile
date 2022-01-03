pipeline{
  agent any stages{
    stage('bulid'){
      steps{
           sh '''
           #! /bin/bash 
           echo "this is the first step to bulid"
           '''
      }
    }
      stage('test calling'){
        steps{
        sh 'echo "this is for calling test"'
        }
      }
        stage('test display'){
          steps{
          sh '''
              #! /bin/bash
              echo " this is second test for display"
            ''' 
          } 
      }
    stage('deploy'){
      steps{
          sh ' echo " Final stages is deployed" '
      }
    }
    
  } 
}
