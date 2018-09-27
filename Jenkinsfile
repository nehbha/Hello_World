pipeline {
  agent any
  stages {
    stage('get code') {
      steps {
        git(url: 'https://github.com/AppSecDev/AltoroJ.git', branch: 'master')
      }
    }
  }
}