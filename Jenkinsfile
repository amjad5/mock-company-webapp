pipeline {
  /*
   * TODO: Implement pipeline stages/steps
   *   See documentation: https://www.jenkins.io/doc/book/pipeline/syntax/#stages
   */
  tools{
    gradle 'Gradle-6.8.2'
  }
  agent any
  stages {
    stage('Build') {
      steps{
        sh './gradlew assemble'
      }
    }
    stage('Test') {
      steps{
        sh './gradlew test'
      }
    }
  }
}
