properties([pipelineTriggers([pollSCM('*/15 * * * *')])])
node {
        stage("one){
                git branch: 'main', url: 'https://github.com/NastyaMor42/MySoftware.git'
    }
}
