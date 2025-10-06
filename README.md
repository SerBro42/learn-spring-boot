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