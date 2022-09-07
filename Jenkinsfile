node('built-in') 
{
    stage('Continuous Download_Master') 
	{
    git 'https://github.com/Arihantjohn/jaji.git'
	}
    stage('Continuous Build_Master') 
	{
    sh label: '', script: 'mvn package'
	}
}
