pipeline
{
    agent any
    stages
    {
        stage('Clone Public Repo')
        {
            steps {
                git branch: 'master',
                    url: 'https://github.com/adityagoel-mata/node-todo-cicd.git'
            }
        }
    }
}
