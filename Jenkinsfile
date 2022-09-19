node('node01'){
    stage('prepare'){
         git credentialsId: 'Github-usr-pwd', url: 'https://github.com/Devops-self-training/jenkins_series-teamcity-batch-helloworld'
    }

    stage('Grant the file'){
        sh 'chmod +xr ./build.bat'
    }
    stage('run the file'){
        sh './build.bat'
    }
}