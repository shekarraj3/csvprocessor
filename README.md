# csvprocessor

name := "CSVparser"

version := "0.1"

scalaVersion := "2.11.6"

// https://mvnrepository.com/artifact/org.apache.spark/spark-core
libraryDependencies += "org.apache.spark" %% "spark-core" % "2.2.0"


// https://mvnrepository.com/artifact/org.apache.spark/spark-sql
libraryDependencies += "org.apache.spark" %% "spark-sql" % "2.2.1"

// https://mvnrepository.com/artifact/org.apache.spark/spark-hive
libraryDependencies += "org.apache.spark" %% "spark-hive" % "2.2.0" % "provided"

libraryDependencies += "joda-time" % "joda-time" % "2.10.1"

libraryDependencies += "com.amazonaws" % "aws-java-sdk" % "1.11.46"
