__Notes:__  
* first part of file name must match class name, case sensitive
* to run the class from the console, we need a method called Main
* 'static' means that this is a member of the class that can be called from the class itself as opposed to a class instance
* notice: Main vs main
* name of method + arguments = method signature
* required main method signature receives an array of strings
* classes are typically organized in packages
* a package is a unique identifier that goes at the top of the class declaration but it actually matches a folder hierarchy

__Sample Run:__  
	javac com\example\java\Main.java  
	java com.example.java.Main potato  
	java com.example.java.Main "potato lemon"
