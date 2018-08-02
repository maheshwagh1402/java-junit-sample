node {
   stage('SCM Checkout') {
   git 'https://github.com/maheshwagh1402/test.git'
}
    stage('Build') {
     def mvnHome = tool name: 'maven', type: 'maven'
      echo 'Hello World'
       sh "${mvnHome}/bin/mvn package"

    }


}
