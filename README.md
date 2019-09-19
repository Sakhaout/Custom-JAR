# Custom-JAR
#SeleniumFunction-1.0.1
#5:45 AM 9/14/2019

I have created some custom jar for my selenium automation. All the common method that I need to use to every where in my framework that all are 
include in this SeleniumFunction-1.0.1 jar file. Such as click(), sendkeys(), close() etc.

In this jar has three class:

	1. SeleniumAction
             	This class has include all common method of selenium webDriver, like toMaximize a browser,
                toDeleteAllCookie, toCloseBrowser etc
                                
         2. ActionsClass
                This class has include all method that is releted to Actions class of selenium WebDriver, like to perform
                doubleClick, rightClick, mouseHover etc.
                                
         3. JavaScriptExecutorClass
            	This class has some method that is related JavaScriptExecutor. To handle hiddenElement, scroolDown a page etc



#Maven Dependency
		<dependency>
			<groupId>selenium.common.method</groupId>
			<artifactId>selenium.common.method</artifactId>
			<version>1.0.1</version>
		</dependency>
