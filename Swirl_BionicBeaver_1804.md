### Fixing the swirl package installation in Ubuntu Bionic Beaver 18.04 LTS

### GO TO Terminal, R and type in the commands below

Terminal

$ sudo apt-get install libcurl4-openssl-dev 

$ sudo apt-get install libssl-dev

R

install.packages("openssl")

install.packages("swirl")

DONE (swirl)

library(swirl)
