node('master') 
{
    stage('Continuous Download_masterr') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous Build_masterr') 
	{
    sh label: '', script: 'mvn package'

    }
  }
