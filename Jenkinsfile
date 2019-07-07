#!bash/sh
/**
@Author 
SridharKumar
**/

node{
    stage('SCM Checkout'){
        git 'https://github.com/galamsiva2020/learncamel-simple-file.git'

}

     stage('Maven Build'){
       def mvnHome = tool name: Maven 3
       sh '$(mvnHome)/bin/mvn package'
}
}
