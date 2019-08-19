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
        bat label: '', script: 'setx JAVA_HOME "C:\Program Files\Java\jdk1.8.0_211"'
        bat label: '', script: 'setx PATH "%PATH%;%JAVA_HOME%\\bin"'
        bat label: '', script: 'javac'
      }
    }
  }
}
