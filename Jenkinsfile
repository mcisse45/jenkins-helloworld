node {
    stage('clone') {
        git 'https://github.com/mcisse45/jenkins-helloworld.git'
  
    }
     stage('Build') {
         sh 'javac Main.java'
   
    }
     stage('Run') {
         sh ' Main.java'
   
    }
}