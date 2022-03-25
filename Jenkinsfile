node{
  stage('SCM Checkout'){
   
    git 'https://github.com/jonathanisgiftofgod/JenkinsExample'
  }
  stage('compile-package'){
    //Get maven home path
     def mvnHome = tool name: '', type: 'maven'
    sh "${mvnHome}/bin/mvn package"
