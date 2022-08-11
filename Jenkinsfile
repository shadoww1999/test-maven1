pipeline{
  agent any
  stages {
  stage('maven install') {
    steps {
      withMaven(globalMavenSettingsConfig: 'dc66a96e-451e-4147-b39f-9cca4ca745b0', jdk: 'JDK installer auto', maven: 'maven3', mavenSettingsConfig: 'f7fd908f-6204-4ca5-b0bb-7dba9b41a586') {
   bat "mvn clean install"
}
    }
  }

}

}
