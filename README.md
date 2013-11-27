openshift-teamcity
==================

This is a DIY cartridge for setting up Teamcity (currently 8.0.5) on Openshift.

###Getting Started

- Create an account with [Openshift](http://openshift.com/)
- Install [RHC client](https://www.openshift.com/developers/rhc-client-tools-install)

####Setup rhc
    rhc setup


####Setup a new Teamcity application
    rhc app create <instance name> diy-0.1 --from-code=git://github.com/sriv/openshift-teamcity.git 

    