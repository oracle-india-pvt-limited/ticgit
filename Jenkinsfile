pipeline {
  agent any
  stages {
    stage('Cloning GIT ') {
      steps {
        echo 'Cloning GIT'
        git(branch: 'master', url: 'https://github.com/oracle-india-pvt-limited/CI-CD-Docker.git')
      }
    }
  }
}