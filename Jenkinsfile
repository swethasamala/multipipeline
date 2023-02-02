properties([
                buildDiscarder(
                        logRotator(
                                artifactDaysToKeepStr: "2",
                                artifactNumToKeepStr: "2",
                                daysToKeepStr: "2",
                                numToKeepStr: "6")
                )
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
