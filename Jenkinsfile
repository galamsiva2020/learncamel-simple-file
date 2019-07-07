#!bash/sh
/**
@Author 
SridharKumar
**/

node{
    stage('SCM Checkout'){
        git 'https://github.com/galamsiva2020/learncamel-simple-file.git'
}
    
    stage('maven-build'){
        //Get maven home path
        def mvnHome = tool name: 'maven-3', type:'maven'
        sh "${mvnHome}/bin/mvn package"
}
}
