node('built-in') 
{
    stage('Continuous Download_note') 
	{
    git 'https://github.com/Arihantjohn/jaji.git'
	}
    stage('Continuous Build_note') 
	{
    sh label: '', script: 'mvn package'
	}
}
