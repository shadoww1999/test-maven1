pipeline{
  agent any
  stages {
  stage('maven install') {
    steps {
      withMaven(globalMavenSettingsConfig: 'null', jdk: 'JDK installer auto', maven: 'maven3', mavenSettingsConfig: 'f7fd908f-6204-4ca5-b0bb-7dba9b41a586') {
   sh 'mvn clean install'
}
    }
  }

}

}
