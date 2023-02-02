properties([
                buildDiscarder(
                        logRotator(
                                numToKeepStr: "10")
                )
                gitLabConnection('gitlab')
        ])
node {  
    stage('Build') { 
        sh """
        echo 'Building'
        """
    }
    stage('Test') { 
        sh"""
        echo 'Testing'
        """
    }
    stage('Deploy') { 
        sh """
        echo 'Deploying'
        """
    }
}
