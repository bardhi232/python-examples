pipeline {

agent { label 'DEVELOPMENT' }

stages {

  stage('Build') {
    steps {
    echo "Build step is getting executed...!!!!"
    }
  }
  stage('Test') {
    steps {
    echo "Test step is getting executed...!!!!"
    }
  }
  stage('Running_Script') {
    steps {
    sh("python basic_examples/python_strings.py")
    }
  }
  stage('Deploy') {
    steps {
    echo "Deploy step is getting executed...!!!!"
    }
  }

}

}