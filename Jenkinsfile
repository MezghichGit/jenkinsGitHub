pipeline {

  agent any

  stages {
    
    stage('récupération depuis github') {
      steps {
        git 'https://github.com/MezghichGit/jenkinsGitHub'
      }
    }

    // Create a new .jar file 

    stage('Un simple message') {

      steps {

        //sh 'mvn clean install -DskipTests'
        echo "Success de pulling du code"

      }

    }
  }
}