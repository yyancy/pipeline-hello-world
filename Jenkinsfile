pipeline {
  agent any
  
  tools {
    maven 'maven-3.5.4'
  }
  
  stages{
    stage('build'){
      steps{
        echo "hello yancy"
        bat 'mvn clean package'
      }
    }
  }

}
