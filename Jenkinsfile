node('master') 
{
    stage('Continuous Download_master.baca') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous Build_master.baca') 
	{
    sh label: '', script: 'mvn package'
	}

}
