java program called HelloFX2 (uses JavaFX) 

Usage: 

C:\> set PATH_TO_FX=C:\Users\account\Downloads\javafx-sdk-25.0.2\lib

C:\> javac --module-path %PATH_TO_FX% --add-modules javafx.controls HelloFX2.java

C:\> java --module-path %PATH_TO_FX% --add-modules javafx.controls HelloFX2

or

$ export PATH_TO_FX=/home/account/download/javafx-sdk-25.0.2/lib

$ javac --module-path $PATH_TO_FX --add-modules javafx.controls HelloFX2.java

$ java --module-path $PATH_TO_FX --add-modules javafx.controls HelloFX2

(><)
