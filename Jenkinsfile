#!/usr/bin/env groovy

pipeline {
  agent any

  stages {
    stage('build') {
      steps {
        sh 'javac -d . *.java'
        }
    }
    stage('run') {
      steps {
        sh 'java HelloWorld'
      }
    }
  }
}