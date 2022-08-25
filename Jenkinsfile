node {
  stage('Checkout SCM'){
    git branch 'master' url 'https://github.com/subbuto/demo-angular-app.git'
  }
  stage('Build'){
    sh "building the application"
  }
  stage('deploy'){
    sh "Deploy the application"
  }
}
