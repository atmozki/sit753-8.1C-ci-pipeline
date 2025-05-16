pipeline {
  agent any
  stages {
    stage('Build') {
      steps { echo 'Using Maven to compile & package the code' }
    }
    stage('Unit & Integration Tests') {
      steps { echo 'Using JUnit for unit tests and Cucumber for integration tests' }
    }
    stage('Code Analysis') {
      steps { echo 'Using SonarQube Scanner for static code analysis' }
    }
    stage('Security Scan') {
      steps { echo 'Using OWASP Dependency-Check (or Snyk) for vulnerability scanning' }
    }
    stage('Deploy to Staging') {
      steps { echo 'Using AWS CLI to deploy to staging' }
    }
    stage('Integration Tests on Staging') {
      steps { echo 'Using Postman for end-to-end API tests' }
    }
    stage('Deploy to Production') {
      steps { echo 'Using Terraform (or AWS CLI) to deploy to production' }
    }
  }
}
// This is a Jenkin file