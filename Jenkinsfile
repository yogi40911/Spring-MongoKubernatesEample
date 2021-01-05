node{
  stage('SCM checkout'){
    git 'https://github.com/yogi40911/Spring-MongoKubernatesEample/new/'
  }
  stage('Build package'){
    sh 'mvn package'
  }
}
