pipeline{
  agent {label 'slavec'}
  stages{
    stage('build'){
      steps{
        sh'''
        cd /home/jenkins/workspace/projectc
        make
        '''
      }
    }
  }
}
