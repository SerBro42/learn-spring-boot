# learn-spring-boot

This is an edit in the README file

This is an edit done in VSC

dev environment
***********************
~~~~~~~~~~~~~~~~
logging.level.org.springframework=trace
~~~~~~~~~~~~~~~~

prod environment
**********************
~~~~~~~~~~~~~~~~
logging.level.org.springframework=info
~~~~~~~~~~~~~~~~

logging levels, sorted from more information printed to less. Applied to most logging frameworks. Every category
prints its own info + the info from all levels below (E.g. Info will print info + warning + error).
********************
trace
debug
info
warning
error
off

********************
Instructions on how to generate and use executable JAR file:
1. gradle clean build
2. The location of JAR file is not listed among the created outputs by default. To find it, go to <project>/build/libs
3. Open a terminal in that directory, or change your current directory to go there.
4. java -jar <name_of_.JAR>
5. If fails, make sure the Java version is up-to-date and that the port is not being used.