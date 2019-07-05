pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'npm install'
      }
    }
  }
  environment {
    JAVA_HOME = 'F:\\Software\\Java\\jdk1.8.0_162'
    MAVEN_HOME = 'F:\\Software\\Maven\\apache-maven-3.3.9'
    GIT = 'F:\\Software\\Git'
  }
}