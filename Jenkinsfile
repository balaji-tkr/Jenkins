@Library('demo-SL@master')_
ansiColor('xterm') {
    echo 'something that outputs ansi colored stuff'
}
pipeline{
  agent any 
    stages{
      stage('compile'){
        steps{
  mvnInstall(currentBuild.getResult())
        }
      }
    }
}
