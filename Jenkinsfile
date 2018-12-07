pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        mail(subject: 's', body: 'b', charset: 'UTF-8', to: 'ningwp@4px.com')
        svn 'svn://172.16.30.16:20040/IronForge/IronForge-Billing/trunk/fpx-ironforge-billing@HEAD'
      }
    }
  }
}