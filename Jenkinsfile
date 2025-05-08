pipeline{
 agent any;
  stages{
    stage('BUILD'){
     agent{ label 'c-project-node' }
      steps{
        echo "This is Build Stage"
      }
    }
   stage('TEST'){
      steps{
        echo "This is test Stage"
      }
    }
    stage('DEPLOY'){
      steps{
        echo "This is deploy Stage"
      }
    }
   
  }
}
