# 2019-03-19

This is a resubmission after expanding the Description per the feedback below.

Thank you,
Alan

# 2019-03-19

Thanks, can you please explain what "WebSocket" is? Perhaps add an URL 
and point to it in the form <http....>?

Best,
Uwe Ligges

# 2019-03-18

This is a new submission.

## Test environments

* local Windows 10 install, R 3.5.3
* Ubuntu 14.04 (on travis-ci), R 3.5.3
* Ubuntu 14.04 (on travis-ci), R-devel

## R CMD check results

There were no ERRORs or WARNINGs.

There were 2 NOTEs:

* installed size is 13.7Mb
  sub-directories of 1Mb or more:
  libs  13.5Mb
  
The websocketpp C++ library object files exceed 1Mb.
    
* GNU make is a SystemRequirements.

GNU syntax += is used in Makevars.in to append to the PKG_LIBS variable.