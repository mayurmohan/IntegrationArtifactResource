@Library('piper-lib-os') _

node() {
  stage('init') {
    deleteDir()
    checkout scm
  }
  stage('deployIntegrationArtifact Command') {
       integrationArtifactResource script: this
  }
}
