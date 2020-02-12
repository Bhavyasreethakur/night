pipeline{
agent any
tools {
  maven 'mavn'
}
  stages{
    stage('clean test'){
      steps{
        sh script: 'mvn clean test'
      }
    }
  }
}
