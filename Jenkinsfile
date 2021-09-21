node{
  stage('scm checkout '){
     git'http://github.com/komminenisaichandu/git-is-available'
  }
  stage('compile-package'){
    //Get maven home path
   defmvnHome = tool name: '', type: 'maven'
    sh "${mvnHome}/bin/mvn package"
        }
        }
