pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        sh '''pwd
cd pytest_demo
source /home/PJLAB/lijialun/.venv/bin/activate
pytest --alluredir=./allure-results'''
      }
    }

  }
}