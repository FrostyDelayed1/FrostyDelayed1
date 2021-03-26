name:Firefoxon:pushjobs:
# hmm, seems when using container user1001 (that should have FF installed)# Cypress cannot find Firefox. This job just prints browser versionscheck-firefox:
runs-on:ubuntu-latest# https://github.com/cypress-io/cypress-docker-imagescontainer:cypress/browsers:node13.6.0-chrome80-ff72steps:
# help us who how we are running in the container -run:whoami -run:id -run:google-chrome --version -run:firefox --version
