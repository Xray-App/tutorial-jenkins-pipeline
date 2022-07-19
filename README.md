# Tutorials for importing tests results to Xray using Jenkins pipeline
[![license](https://img.shields.io/badge/License-BSD%203--Clause-green.svg)](https://opensource.org/licenses/BSD-3-Clause)
[![Gitter chat](https://badges.gitter.im/gitterHQ/gitter.png)](https://gitter.im/Xray-App/community)

## Overview
Here you can find the examples that showcase how to import test results using the Jenkins pipeline into [Xray](https://www.getxray.app/) on Jira. There are small differences depending on whether you're using Xray cloud or Xray server/DC.

This code is divided into two directories with multiple examples that supports two tutorials:
- [./cloud](cloud) - If you are using the cloud version of Xray; detailed info in [Examples using Jenkins pipeline](https://docs.getxray.app/display/XRAYCLOUD/Jenkins+pipeline+integration) 
- [./server](server) - If you are using the Server/DC version of Xray; detailed info in [Examples using Jenkins pipeline](https://docs.getxray.app/display/XRAY/Jenkins+pipeline+integration)


## Prerequisites
In order to import tests you need to have a Jira instance with Xray installed and have the proper permissions; please check Xray documentation for more info. You need a Jenkins instance with Xray plugin installed.

## Running
All the files in this repository can be imported through the Jenkins pipeline. Please make sure you chose files from the correct Xray deployment type (cloud or server/DC).

## Contact

Any questions related with this code, please raise issues in this GitHub project. Feel free to contribute and submit PR's.
For Xray specific questions, please contact [Xray's support team](https://jira.getxray.app/servicedesk/customer/portal/2).

## References

Xray Cloud:
- [Jenkins pipeline integration](https://docs.getxray.app/display/XRAYCLOUD/Jenkins+pipeline+integration)
- [Integration with Jenkins](https://docs.getxray.app/display/XRAYCLOUD/Integration+with+Jenkins)

Xray server/DC:
- [Jenkins pipeline integration](https://docs.getxray.app/display/XRAY/Jenkins+pipeline+integration)
- [Integration with Jenkins](https://docs.getxray.app/display/XRAY/Integration+with+Jenkins)


## LICENSE

[BSD 3-Clause](LICENSE)
