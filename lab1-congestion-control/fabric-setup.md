Fabric Setup
=============

In this tutorial, you will learn how to use FABRIC to run experiments in computer networks or cloud computing. It should take you about 60-90 minutes of _active_ time to work through this tutorial.

> **Note** This process has multiple “human in the loop” approval stages - you’ll need to wait for FABRIC staff to approve your account, and then again for your your instructor or research advisor to add you to their project. Be prepared to start the tutorial, wait for this approval, and then continue.

FABRIC is a “virtual lab” for experiments on networking, cloud computing, and distributed systems. It allows experimenters to set up real (not simulated!) hosts and links at FABRIC sites located around the United States. Experimenters can then log in to the hosts associated with their experiment and install software, run applications, and collect measurements.

Before you can run lab experiments on FABRIC, you will need to set up an account. Once you have completed the steps on this page, you will have an account that you can use for future experiments. This experiment will also demonstrate the process of “reserving” resources on a FABRIC site, logging in to a host on FABRIC, retrieving a file (such as data from an experiment) from a FABRIC host, and deleting your reserved resources to free them for other users.

Set up your account on FABRIC
-----------------------------

Follow the instructions (here)[https://learn.fabric-testbed.net/knowledge-base/signing-up-for-a-fabric-account/] to register.

You should use your Pitt institutional login (Search for "University of Pittsburgh") to register your account.

Important: You MUST respond to the FABRIC approval email within 24 hours to activate your account. You must also complete the second part of the instructions and login to the FABRIC portal after receiving your approval email. Otherwise, We will not be able to add you to the course project to give you access to the lab environment.

To use FABRIC, you need to be a part of a project that has been approved by the FABRIC staff, under the supervision of a project lead who supervises your use of FABRIC.

If you click on the “Projects” tab in the FABRIC portal dashboard (while logged in to your FABRIC account), you’ll see a list of projects that you belong to. If your account was set up correctly, you should be able to see a project with the name "CS 2520 Fall 2025" and description "For labs in the University of Pittsburgh course CS 2520 / TELCOM 2321: Wide Area Networks". Make sure you have this project listed on this page before continuing further.

### FABRIC JupyterHub

Once you are part of a FABRIC project, you can reserve resources on FABRIC and access them over SSH! We’ll use FABRIC’s Jupyter environment for this.

Log on to the [FABRIC Portal](https://portal.fabric-testbed.net/), then click on the “JupyterHub” menu option. You may be prompted to log in again. You may have to select which version of the FABRIC JupyterHub you want to launch, and you can select the default version.

To continue working on this tutorial, download "pre-lab1.ipynb" file and work through it inside a terminal on JupyterHub.

In the Jupyter environment on Fabric, select File > New > Terminal and in this terminal, run

    git clone <TODO: add our link>

Then, in the file browser on the left side, open the fabric-setup directory and then double-click on the fabric-setup.ipynb notebook to open it.

If you are prompted about a choice of kernel, you can accept the Python3 kernel.

Then, you can continue this tutorial by executing the cells in the notebook directly in this Jupyter environment.

### Acknowledgment
Adapted from Fraida Fund's [Teaching on Testbeds](https://teaching-on-testbeds.github.io/hello-fabric/)'s page ["Hello, FABRIC"](https://teaching-on-testbeds.github.io/hello-fabric/).