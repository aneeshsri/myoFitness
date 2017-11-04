# myoFitness

Mental Health and well-being (physical fitness is best preventative measure and solution to this):

You tell computer speech recognition api that you want to do workout 1
It tells you to do X number of pushups, and tells you to get in push up position and then say start
You get into push up position and say start
It turns on MYOController
You say finish
It closes MYOController, It looks at graph (number of times orientation-euler graph’s roll exceeded 1.9 on the y-axis)
It then tells that number ^^ of push-ups done and records it
	  If this number is >= X number of pushups, good
	  Else if this number < X number of pushups, then:
		    It donates $1 every time to CMHA
