# java2smali
Guide to covert java, .class file to smali

javac HelloWorld.java

dx --dex --output=classes.dex HelloWorld.class

baksmali d classes.dex
