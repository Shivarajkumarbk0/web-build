pipeline{
  agent any
  tools{
    maven 'maven'
  }

  stages{
    stage("mvn"){
      steps{
        sh 'mvn clean'
      }
    }
    stage("package"){
      steps{
        sh 'mvn package'
      }
    }
  }
}
      
