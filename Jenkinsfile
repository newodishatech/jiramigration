pipeline{
  agent any
  stages{
    stage("Inside Jenkinsfile"){
      steps{
        bat label: '', script: 'echo inside jenkinsfile %strname%'
      }
    }
    stage("Printing Parameter"){
      steps{
        bat label: '', script: 'echo Parameter is: %strname%'
      }
    }
    stage("Checking Maven"){
      steps{
        bat label: '', script: 'mvn --version'
      }
    }
  }
}
