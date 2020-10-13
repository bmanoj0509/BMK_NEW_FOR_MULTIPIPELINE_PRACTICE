node ('master')
{
   stage('continuous download on master')
   {
       git 'https://github.com/bmanoj0509/BMK_NEW.git'
   }
   stage('continuous build on master')
   {
       sh 'mvn package '
   }
}
