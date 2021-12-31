properties([pipelineTriggers([pollSCM('30 * * * *')])])
node{
    stage("exercise"){
        checkout([$class: 'GitSCM', branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/illy-birenz/MySoftware.git']]])
    }
	stage("for fun"){
	echo doing nothing
	}
}