node
{
    def applicationTitle = 'Learning class1';
    stage('Checkout Code')
    {
        git branch:'master' , url:'https://github.com/Deepinder1996/devops-project1.git'
    }

    stage('Copy HTML')
    {
        sh 'cp index.html /var/www/html/'
    }
    stage('Notify Email')
    {
        sh 'echo Sending email'
    }
}
