node {
    stage('Release') { 
        git 'https://github.com/jstrachan/updatebot-npm-sample.git'

    }
    stage('UpdateBot') {
        // now lets make pull requests on downstream projects
        updateBotPush
    }
}
    
