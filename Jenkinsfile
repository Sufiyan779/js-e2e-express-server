pipeline
{
    agent (label 'OPENJDK-11-4')
triggers
{
    pollSCM ('* * * * *')
}
stages{
    stage ('pull from vcs')
    {
        steps{
            git url: ''
        }

    }
}
}