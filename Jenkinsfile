@Library('demo-SL@master')_

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
