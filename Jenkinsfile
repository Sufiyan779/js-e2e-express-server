pipeline
{
    agent (label 'OPENJDK-11-4')
triggers
{
    pollSCM ('* * * * *')
}
stages
{
    stage ('pull from vcs')
    {
        steps
        {
            git url: 'https://github.com/Sufiyan779/js-e2e-express-server.git',
            branch: 'javaScript'
        }

    }
    stage('build')
    {
     steps
     {
        sh 'nvm package'
     }
    }
}
}