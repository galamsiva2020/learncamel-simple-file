#!bash/sh
/**
@Author 
SridharKumar
**/

node{
    def scannerHome
    stage('SCM Checkout'){
        git 'https://github.com/galamsiva2020/learncamel-simple-file.git'
}
    
    stage('maven-build'){
        //Get maven home path
        //def mvnHome = tool name: 'maven-3', type:'maven'
        mvnHome ='D:/GALAM/SivaDevopsSoftwares/apache-maven-3.6.0-bin/apache-maven-3.6.0'
        //sh "${mvnHome}/bin/mvn package"
}
    
  //  stage('TestResults') {
    //  junit '**/target/surefire-reports/TEST-*.xml'
     // archiveArtifacts 'target/*.jar'
   //}
    
   // stage('SonarQube analysis') {
    scannerHome= 'D:/GALAM/sonarqube-6.2/sonarqube-6.2/bin/windows-x86-64'
    //def scannerHome = tool 'SonarScanner 2.8';
    //withSonarQubeEnv('My SonarQube Server') { // If you have configured more than one global server connection, you can specify its name
      //sh "${scannerHome}/bin/sonar-scanner"
  //  }
  //}
}
