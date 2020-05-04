node{
   stage('SCM Checkout'){
     git 'https://github.com/gokiramu/Heloworld' 
   }
   stage('Compile-Package'){
      sh 'mvn package'
   }

}
