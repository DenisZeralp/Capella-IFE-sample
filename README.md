<!--
 ~ SPDX-FileCopyrightText: Copyright DB InfraGO AG
 ~ SPDX-License-Identifier: Apache-2.0
 -->

In-Flight Entertainment System sample model
===========================================

This repo contains the "In-Flight Entertainment System" sample model,
originally maintained by the Capella developers at
<https://github.com/eclipse-capella/capella/tree/master/samples/In-Flight%20Entertainment%20System>.

This repo also contains some adjustments to the model as well as additional
configuration to showcase some features of
[py-capellambse](https://github.com/DSD-DBS/py-capellambse).

Pulling updates
---------------

The repo history was extracted from the upstream Capella model using `git
subtree`, and can be updated by repeating the process.

```sh
# Clone the upstream repo
git clone https://github.com/eclipse-capella/capella.git
cd capella
git subtree split -P "samples/In-Flight Entertainment System" -b ife-demo

# In this repo:
git pull ../capella ife-demo
```

Licensing
---------

The model itself is licensed under the [Eclipse Public License
2.0](LICENSES/EPL-2.0.txt).

Most other files are licensed under the [Apache-2.0](LICENSES/Apache-2.0.txt)
license. For details, please refer to the copyright statements attached to each
file, as described by the [REUSE Specification Version
3.2](https://reuse.software/spec-3.2/).
