This program and the accompanying materials are
made available under the terms of the Eclipse Public License v2.0 which accompanies
this distribution, and is available at https://www.eclipse.org/legal/epl-v20.html

SPDX-License-Identifier: EPL-2.0

Copyright Contributors to the Zowe Project.

# ZSS IPL plug-in

## Overview

A sample plug-in that allows:
* Returning z/OS address spaces using the following REST endpoint

```
GET http://zsshost:zssport/ZLUX/plugins/org.zowe.zsssample/services/sample/asinfo
```
* Dumping z/OS address spaces using the following REST endpoint



### Getting the code:
* Use the following command to clone this repository with all the dependencies:
```
git clone --recursive git@github.com:ifakhrutdinov/zss-sample-plugin.git
```

### Building and deploying the ZSS plug-in:
  * Go to the build directory in zssServer/build
  * Run build.sh
  * Run deploy.sh
  * Restart your ZSS


This program and the accompanying materials are
made available under the terms of the Eclipse Public License v2.0 which accompanies
this distribution, and is available at https://www.eclipse.org/legal/epl-v20.html

SPDX-License-Identifier: EPL-2.0

Copyright Contributors to the Zowe Project.
