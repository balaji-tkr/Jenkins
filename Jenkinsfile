@Library('demo-SL@master')_

pipeline{
  agent any 
    stages{
      stage('compile'){
        steps{
mvnCompile(currentBuild.getResult())
          //mvnInstall(currentBuild.getResult())
        }
      }
    }
}
