node('node01'){
    stage('prepare'){
         git credentialsId: 'Github-usr-pwd', url: 'https://github.com/Devops-self-training/jenkins_series-teamcity-batch-helloworld'
    }

    stage('testing'){
        sh 'echo "helloworld"'
    }
}