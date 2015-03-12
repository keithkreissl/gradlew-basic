# gradlew-basic application
___

* This basic application shows how to set up and use the gradle wrapper 
* https://spring.io/guides/gs/gradle/#scratch
* http://assemble.io/docs/Cheatsheet-Markdown.html

# Gradle Wrapper
___
* look at the last line of the build.gradle file for the wrapper task that will pull in the version of gradle to build with
* this will allow any platform to download the specific version of gradle and run right off the bat
* now you can use ./gradlew {task} from command line without having gradle installed

# application plugin
___
* apply plugin: 'application'
* mainClassName: '{class name}'
* This will make the jar executable using ./gradlew run

