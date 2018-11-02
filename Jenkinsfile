@Library('demo-SL@master')_
//mvnInstall(currentBuild.getResult())
pipeline{
  agent any 
    stages{
      stage('compile'){
        steps{
mvnCompile(currentBuild.getResult())
        }
      }
    }
}
