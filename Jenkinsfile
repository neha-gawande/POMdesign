pipeline {
    agent any 
    stages {
        stage('Run on DEV') {
            parallel {
                stage('Run on DEV')
            steps {
                sh 'echo "Run on DEV"'
            }
        }
        stage('Chrome') { 
            steps {
                sh 'echo "Run on Chrome"'
            }
          }
        }
    }
    stage('Run on QA') {
            parallel {
                stage('Run on QA')
            steps {
                sh 'echo "Run on QA"'
            }
        }
        stage('Chrome') { 
            steps {
                sh 'echo "Run on Chrome"'
            }
        }
         stage('firefox') { 
            steps {
                sh 'echo "Run on FF"'
            } 
           }
        }
      }
        stage('Run on stage') {
            parallel {
                stage('Run on stage')
            steps {
                sh 'echo "Run on stage"'
            }
        }
        stage('Chrome') { 
            steps {
                sh 'echo "Run on Chrome"'
            }
        }
         stage('firefox') { 
            steps {
                sh 'echo "Run on FF"'
            } 
           }
         stage('stage') { 
            steps {
                sh 'echo "Run on safari"'
            } 
           }
        }
      }
        stage('Run on PROD') {
            parallel {
                stage('Run on PROD')
            steps {
                sh 'echo "Run on prod"'
            }
        }
        stage('Chrome') { 
            steps {
                sh 'echo "Run on Chrome"'
            }
        }
        }
}
}
tools{
    maven 'M3'
}
}
        stage('Deploy') { 
            steps {
                // 
            }
        }
    }
}
