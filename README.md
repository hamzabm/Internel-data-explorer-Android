# Internal-explorer
[![](https://jitpack.io/v/hamzabm/internal-explorer.svg)](https://jitpack.io/#hamzabm/internal-explorer)

## Setup

The simplest way to add Internal Explorer to your app is to add the library as aar dependency to your build.


**Gradle**

    allprojects {
    	repositories {
    		maven { url 'https://jitpack.io' }
    	}
    }

    dependencies {
          implementation 'com.github.hamzabm:internal-explorer:0.1-beta'
    }

## Usage

  Show Explorer of Path passed in parameters

    InternalDataExplorer(path,activity).launch()
    
   then you will be able to : 
    - delete files
    - export files
    - import files
    - create folders
    

    
## Example

we need to display the content of this.filesDir
    
        InternalDataExplorer(this.filesDir.absolutePath,thid).launch()

![image](https://github.com/hamzabm/internal-explorer/blob/main/doc/tuto.gif)





