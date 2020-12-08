pipeline{
    agent any
    stages{
      stage('Build'){
          steps{
          echo 'Build Stage'
          }
      }
      stage('clean'){
          steps{
          bat 'mvn clean'
          }
      }
      stage('test'){
          steps{
          bat 'mvn test'
          }
      }
      stage('install'){
          steps{
          bat 'mvn install'
          }
      }
    }
}
