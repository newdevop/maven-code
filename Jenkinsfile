pipeline {
    agent any
     stages{
      stage('clean'){
       steps {
         sh "mvn clean"
       }
    }
    stage('complile'){
       steps {
         sh "mvn compile"
       }
    }
    stage('install'){
       steps {
         sh "mvn install"
         sh "mvn package"

       }
    }
    
    }

}
