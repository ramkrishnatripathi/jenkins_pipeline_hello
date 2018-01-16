node {
   stage('Stage 1'){
   		echo 'Hello World 1'
   }  
   stage('Stage 2'){
   		echo 'Hello World 2'
   }   
   stage("Parallel") {
       steps {
           parallel (
               "firstTask" : {
                   echo "Executing 1 firstTask.........."
               },
               "secondTask" : {
                  echo "Executing 1 secondTask.........."
               }
           )
       }
   }
}
