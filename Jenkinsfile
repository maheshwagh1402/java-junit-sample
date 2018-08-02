node {
   stage('SCM Checkout') {
   git 'https://github.com/maheshwagh1402/java-junit-sample.git'
}
    stage('Build') {
     def mvnHome = tool name: 'maven', type: 'maven'
      echo 'Hello World'
       sh "${mvnHome}/bin/mvn package"

    }
   stage('Test') {
      echo 'Testing Project..'
      sh "${mvnHome}/bin/mvn test"

}
