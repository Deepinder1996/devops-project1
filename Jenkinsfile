node
{
    def application title = 'Learning class1';
    stage('Checkout Code')
    {
        git branch:'master' , url:'https://github.com/Deepinder1996/devops-project1.git'
    }

    stage('Copy HTML')
    {
        sh 'sudo cp index.html /var/www/html/'
    }
    stage ('Copy Images')
    {
        sh 'sudo cp -r images/ /var/www/html/'
    }
    stage('Notify Email')
    {
        sh 'Sending email'
    }
}