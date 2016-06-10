node {
  stage 'Build and Test'
  env.PATH = "${tool 'maven-3.3.9'}/bin:${env.PATH}"
  checkout scm
  sh 'mvn clean package'
}
