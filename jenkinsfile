stages {
  stage('build image') {
    steps {
      // One or more steps need to be included within the steps block.
    }

    agent {
      dockerfile {
        dir 'cicd-k8s'
        filename 'Dockerfile'
        registryUrl 'https://hub.docker.com/r/deyaa/app'
      }
    }
  }

}
