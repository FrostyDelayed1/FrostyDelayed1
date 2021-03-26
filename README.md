name:Firefoxon:pushjobs:
# hmm, seems when using container Cypress cannot find Firefox. This job just prints browser versionscheck-firefox:
runs-on:ubuntu-latest# https://github.com/cypress-io/github-action/pull/98
# help us who how we are running in the container -run:whoami -run:id -run:google-chrome --version -run:firefox --version
