Active Directory Authentication Library (ADAL) for JavaScript
====================================
[![Build Status](https://travis-ci.org/taarskog/adal-angular-for-crm-webresources.svg?branch=master)](https://travis-ci.org/taarskog/adal-angular-for-crm-webresources)

## IMPORTANT!
This fork is no longer active. [crm-powerbi-viewer](http://crm-powerbi-viewer.heiigjen.com/) which used to have a dependency on this fork have implemented an alternative
approach. Thus this fork will no longer be maintained. 

## Fork information
This is a fork of [azure-activedirectory-library-for-js](https://github.com/AzureAD/azure-activedirectory-library-for-js) with just one minor modification to enable
the lib to be used in Dynamics CRM web resources. In this situation the lib should not handle tokens against CRM - only towards external resources such as Power BI.
