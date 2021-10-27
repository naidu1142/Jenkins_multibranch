node('master') 
{
    stage('Continuous Master') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous Build')
    	{
    sh label: '', script: 'mvn package'
    	}
}
