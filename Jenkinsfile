node{
stage('SCM Checkout'){
  git 'https://github.com/Skolagotla1/simple-java-maven-app'
}
stage('Compile Package'){
  def mvnnew = tool name: 'Maven', type: 'maven'
  sh "${mvnnew}/bin/mvn package"
}
}
