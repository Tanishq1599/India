pipeline {
    agent any

    stages 
    {
        stage('Build') 
        {
            steps 
            {
                echo 'Build App'
            }
            }
            stage('Test') 
            {
            steps 
            {
                echo 'Test App'
            }
        }
        stage('QA') 
        {
            steps 
            {
                echo 'QA checking'
            }
    }
}
post
{
always
{
emailext body: 'The pipeline name "First Pipeline". Check Status', subject: 'Pipeline Status', to: 'tanishqdeshpande01@gmail.com'
}
}
}
