pipeline {
    agent {
        dockerfile {
            filename 'build.Dockerfile'
        }
    }
    stages {
        stage('Test') {
            steps {
                sh '''
          go version
          git --version
          curl --version
        '''
            }
        }
    }
}
