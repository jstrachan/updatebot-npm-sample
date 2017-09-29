node {
    stage('Release') { 
        git 'https://github.com/jstrachan-testing/updatebot-npm-sample.git'

        // TODO do the actual release first...
    }
    stage('UpdateBot') {
        // now lets push the release out
        updateBotPush()
    }
}
    
