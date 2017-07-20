node {
   stage 'Stage 1'
   		echo 'Hello World 1'
   parallel(firstTask: {
   		// Do some stuff
			echo 'parallel 1'
   }, secondTask: {
   		// Do some other stuff
			echo 'parallel 2'
   })
   stage 'Stage 2'
   		echo 'Hello World 2'
   stage 'Stage 3'
   		sh 'npm install'
   stage 'Stage 4'
   		sh 'npm test'
}