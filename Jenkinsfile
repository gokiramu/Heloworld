node{
   stage('SCM Checkout'){
     git 'https://github.com/gokiramu/Heloworld' 
   }
   stage('Compile-Package'){
      // Get maven home path
     def mvnHome " tool name: '', type: 'maven'
      sh "${mvnHome}/bin/mvn package"
   } 
   
}
