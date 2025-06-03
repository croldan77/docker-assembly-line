pipeline {
  agent { docker "maven:3.9.9-eclipse-temurin-24-noble" }

  stages {
    stage('maven') {
      steps {
        sh "mvn -version"
        sh "java -version"
      }
    }
  }
}
