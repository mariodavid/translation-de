# translation-de
German translation of CUBA Platform implemented as application component

## Installation

1. Add the following maven repository `https://dl.bintray.com/balvi/cuba-components` to the build.gradle of your CUBA application:

```groovy
    buildscript {
        
        //...
        
        repositories {
        
            // ...
        
            maven {
                url  "https://dl.bintray.com/balvi/cuba-components"
            }
        }
        
        // ...
    }
```

2. Select a version of the add-on which is compatible with the platform version used in your project:

| Platform Version | Add-on Version |
| ---------------- | -------------- |
| 6.7.x            | 1.0.x          |

The latest version is: `1.0.0`

Add custom application component to your project:

* Artifact group: `de.balvi.cuba.translationde`
* Artifact name: `translation-de-global`
* Version: *add-on version*

```groovy
dependencies {
  appComponent("de.balvi.cuba.translationde:translation-de-global:1.0.0")
  [...]
}
```