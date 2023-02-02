properties([buildDiscarder(logRotator(artifactDaysToKeepStr: '', artifactNumToKeepStr: '', daysToKeepStr: '10', numToKeepStr: '5')), [$class: 'ScannerJobProperty', doNotScan: false]])
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
