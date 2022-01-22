node('built-in') 
{
    stage('Continuous Download') 
	{
    git 'https://github.com/dayasanjay/jenkins-multibranch.git'
	}
    stage('Continuous Build') 
	{
    sh label: '', script: 'mvn package'
	}
}
