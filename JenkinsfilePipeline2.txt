pipeline{
  agent any
  stages{
  stage ('BUILD'){
    steps{
        echo 'Build stage'
    }
  }
  stage ('TEST'){
    steps{
        echo 'Test stage'
    }
  }
  stage ('DEPLOY'){
    steps{
        echo 'Deploy stage'
    }
  }
  }
  

}