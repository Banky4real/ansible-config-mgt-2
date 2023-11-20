# ansible-config-mgt-2

Changes Made
Elastic IP
ansible-config-artifact
Updating 
save artifacts
done deal
elk
#### Jenkins file for Quick Task
===========================================
'''
pipeline {
    agent any


  stages {
    stage('Build') {
      steps {
        script {
          sh 'echo "Building Stage"'
        }
      }
    }

    stage('Test') {
      steps {
        script {
          sh 'echo "Testing Stage"'
        }
      }
    }

    stage('Package') {
      steps {
        script {
          sh 'echo "Packaging Stage"'
        }
      }
    }

    stage('Deploy') {
      steps {
        script {
          sh 'echo "Deploy Stage"'
        }
      }
    }

    stage('Cleanup') {
      steps {
        script {
          sh 'echo "Cleanup Stage"'
        }        
      }
    }

    }
}
'''