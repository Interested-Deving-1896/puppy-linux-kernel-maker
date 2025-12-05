This is a just a simple online tool for creating custom kernel for Puppy Linux

How to use this:
* Fork this repo
* Edit .config files
* Go to Actions
* On action sidebar, select workflow and click Run Workflow.
* Select repo branch and click click Run Workflow
* Wait until the process is finished
* Click All Workflows to see the build progress
* Once complete, On "All workflows" select the finished workflow.
* Go to artifacts section to download the output build

There are three workflow files:
* firmware-driver.yml - for creating linux firmware driver
* linux-kernel.yml - for creating linux kernel without any patches
* linux-kernel-aufs.yml - for creating linux kernel with AUFS patch

Tips: If there is a new linux kernel version. Or want to compile other kernel version. Just create new branch and edit the environment section of workflow files. Then run workflow on the newly created branch

NOTE: This tool follows github workflow rules. For github free version, there are 33 hours of runtime hours per month
