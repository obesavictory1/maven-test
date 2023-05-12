pipeline {
    agent any
     stages{
      stage('Hello'){
       steps {
         echo "Hello World"
       }
    }
    stages('build'){
      steps {
        sh 'mvn clean'
      }
    }
    }

}
