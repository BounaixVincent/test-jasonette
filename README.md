#ANDROID STUDIO

## CONFIG

 1) build.gradle : 

  Repositories must be ordered this way :

    repositories {
        google()
        maven {
            url 'https://maven.google.com/'
            name 'Google'
        }
        jcenter()
    }


  Dependencies :
    Classpath for android tools must be 'com.android.tools.build:gradle:3.1.3'

2) Where must be the JSON URL ?

  res -> values -> strings.xml

## ISSUES

-Images displayed in the footer are unicolored. Unlike our logos.
-I don't know how to create a backward button