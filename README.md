# exceptionHandlingInJava

## printStackTrace vs fillInStackTrack

As you know, in a call stack, the last method called is at the top of the stack and the first method called is in the bottom. Then, if an exception occured in some method, it will propagate from top to bottom of the call stack untill it is caught at some point. So, when you catch the exception and call the e.printStackTrace() it shows how the call stack looks like from the point that the exception occured. So, when you call the fillInStackTrace it will change this "point that the exception occured" to the line that the e.fillInStackTrace(); called. This is the meaning of the StackTrace Reset