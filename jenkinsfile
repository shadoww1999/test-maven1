pipeline{
  agent any
  stages {
  stage('maven install') {
    steps {
      withMaven(globalMavenSettingsConfig: 'null', jdk: 'JDK installer auto', maven: 'maven3', mavenSettingsConfig: 'null') {
   sh 'mvn clean install'
}
    }
  }

}

}
