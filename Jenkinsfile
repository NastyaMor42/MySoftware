properties([pipelineTriggers([pollSCM('*/15 * * * *')])])
node {
        stage("clone"){
                git branch: 'main', url: 'https://github.com/NastyaMor42/MySoftware.git'
    }
        stage("click"){
                python3 'click.py'
       }
}
