properties([gitLabConnection('gitlab'), buildDiscarder(logRotator(numToKeepStr: "5"))])
// properties([gitLabConnection('gitlab')])
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
