node {
stage('SCM Chekout'){

 git 'https://github.com/codenaresh/java_jenkins'

}

stage ('compile package'){
 
 def mvnHome=tool name: 'maven-3', type: 'maven'
 
 sh "${mvnHome}/bin/maven package
}
}
