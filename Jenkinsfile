pipeline{
  agent {label 'slavec'}
  stages{
    stage('clone_stage'){
      steps{
        echo "clone stage"
      }
    }
    stage('build_stage'){
      steps{
        sh '''
        cd /home/jenkins/workspace/workspace/projectc
        make
        '''
      }
    }
  }
}
