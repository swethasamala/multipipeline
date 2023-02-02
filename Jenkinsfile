properties([
        buildDiscarder(
                logRotator(
                        artifactDaysToKeepStr: "10",
                        artifactNumToKeepStr: "50",
                        daysToKeepStr: "10",
                        numToKeepStr: "50")
        )
])
properties([gitLabConnection('gitlab')])
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
