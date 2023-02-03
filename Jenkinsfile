pipeline{
        agent any
        stages{
            stage('Build'){
                steps{
                    #sh 'mvn package'
                }
	        }
            stage('Docker Build'){
                steps{
                    #sh 'docker-compose up'
                }
	        }
	        }
            stage('Run App'){
                steps{
                    #sh "JENKINS_NODE_COOKIE=dontKillMe nohup docker run -d ..... &"
                }
	        }
        }
}