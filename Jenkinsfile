node(){
 try {
 stage('Checkout'){
 checkout scm
 }
 stage('Build'){
 echo "Building artifact"
 }
 stage('Push'){
 echo "Storing artifact"
 }
 stage('Deploy'){
 echo "Deploying artifact"
 }
 } catch(err){
 echo "Handling errors"
 } finally{
 echo "Cleaning up"
 }
}
