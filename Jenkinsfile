pipeline
{
    agent any
    stages
    {
        stage('Clone Public Repo')
        {
            steps {
                git branch: 'master',
                    url: 'https://github.com/<username>/<repoName>'
            }
        }
    }
}
