pipeline {
    agent any
    stages {
        stage('Initialize') {
            steps {
                //enable remote triggers
                script {
                    properties([pipelineTriggers([pollSCM('* * * * *')])])
                }
                stage('build'){
                    steps {
                        
                      echo 'hellow'
                    }
                
                                 
                }
                //define scm connection for polling
                git branch: 'main', credentialsId: 'cb3a0841-0476-494c-b8df-1f2ea6cebcd3', url: 'https://github.com/JaleelBasha123/Publicrepo1.git'
            }
        }
    }
}
