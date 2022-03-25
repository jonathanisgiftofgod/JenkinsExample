node{
  stage('SCM Checkout'){
    git 'https://github.com/jonathanisgiftofgod/JenkinsExample'
  }
  stage('compile-package'){
    sh 'mvn package'
