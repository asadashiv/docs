pipeline{
  agent {label 'slavec'}
  stages{
    stage('build'){
      steps{
        sh '''
       cd /home/jenkins/workspace/build1
       make
        '''
      }
    }
  }
}
