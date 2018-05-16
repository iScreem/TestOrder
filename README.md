# TestOrder
Alexa V2 Order of Operations Test

confirmed through console logs that order of operations were
1. CanHandle
2. RequestInterceptor
3. Handle

Using ASK-CLI I created a new skill. 
I simply added a RequestInterceptor with only a console log statement. 
I also added a console log statement to LaunchRequest canHandle and Handle. 
Viewed the cloudwatch log and got order of operations.

I thought that RequestInterceptor would fire first in case you needed to set values for canHandle to check and handle to use.

