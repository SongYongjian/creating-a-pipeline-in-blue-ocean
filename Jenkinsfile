pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        bat(encoding: 'utf-8', script: 'cd /d D:\\hand')
      }
    }
  }
  environment {
    JAVA_HOME = 'F:\\Software\\Java\\jdk1.8.0_162'
    MAVEN_HOME = 'F:\\Software\\Maven\\apache-maven-3.3.9'
    GIT = 'F:\\Software\\Git'
  }
}