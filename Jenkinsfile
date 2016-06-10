node {
  stage 'Build and Test'
  jdk = tool name: 'jdk-8'
  env.JAVA_HOME = "${jdk}"
  env.PATH = "${tool 'maven-3.3.9'}/bin:${env.PATH}"
  checkout scm
  sh 'mvn clean package'
}
