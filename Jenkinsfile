node {
  stage 'Build and Skip Test'  
  checkout scm
  sh 'mvn clean install -DskipTests'
  sh 'which docker'
}