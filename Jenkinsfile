pipeline {
  agent {
    dockerfile {
      filename 'Dockerfile'
      registryUrl 'https://hub.docker.com/r/deyaa/app'
    }
  }
  stages {
    stage ('push') {
      steps {
        echo 'hello world'
      }
    }
  }
}
