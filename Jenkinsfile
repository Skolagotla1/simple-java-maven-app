node{
stage('SCM Checkout'){
  git 'https://github.com/Skolagotla1/simple-java-maven-app'
}
stage('Compile Package'){
  def mvn=tool name: 'Maven', type: 'maven'
sh "mvn package"
}
}
