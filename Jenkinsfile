pipeline{
  agent {label 'slavec'}
  stages{
    stage('clone'){
      steps{
        echo "clone stage"
      }
    }
    stage('build'){
      steps{
        sh '''
        cd /home/jenkins/workspace/workspace/projectc
        make
        '''
      }
    }
  }
}
