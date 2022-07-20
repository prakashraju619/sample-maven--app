pipeline {
 
agent any
 tool {name: 'mvn-jenkins', type: 'maven'}

  stages {
    stage('Cloning Git') {
      steps {
       git branch: 'master', credentialsId: 'b6513267-59ef-425c-8e59-d55f0028ff9e', url: 'https://github.com/prakashraju619/sample-maven--app'
       

      }
    }

    stage('Image Build') {
      steps {
        script {
           
        }

      }
    }

    stage('Docker  Run') {
      steps {
        script {
          
        }

      }
    }
   
   
    }
    
  }
