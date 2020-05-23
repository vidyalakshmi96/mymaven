node('master') 
{
    stage('ConDownload_loans')
    {
        git 'https://github.com/intelliqittrainings/maven.git'
    }
    stage('ConBuild_loans')
    {
        sh label: '', script: 'mvn package'  
    }

}
