node('built-in') 
{
    stage('Continuous Download_note') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous Build_note') 
	{
    sh label: '', script: 'mvn package'
	}
}
