![APPD LOGO](./assets/images/appd-logo.png)

![Lab Icon](./assets/images/lab-icon.png) Browser Real User Monitoring Fundamentals
=========================================================================

## Objectives

In this Lab you learn how to use AppDynamics to monitor the health of your browser based application. You will learn how to configure the Browser Real User Monitoring (BRUM) agent to monitor your web application's health, how to troubleshoot performance issues and find the root cause, whether it occurs on the browser side or the server side of the transaction.


## Prerequisites

You should already have access to the virtual machines for the lab.  If do not already have access to the VMs for the lab, follow the instructions [here](lab-exercise-00.md).

  
- You will need to use the same two virtual machines you used in the [Java Application Monitoring Fundamentals Lab](../fnd-01-appd-apm-java/lab-exercise-01.md)
- This Lab has dependencies associated with the Java Application Monitoring Fundamentals Lab
- Please complete the Java Application Monitoring Fundamentals Lab before you proceed with this Lab if you have not already done so.


## Lab Contents
This lab covers five main areas:

1. Check the lab prerequisites 
2. Create a browser application in the Controller
3. Configure the browser agent injection settings
4. Monitor and troubleshoot Browser App issues - Part 1
5. Monitor and troubleshoot Browser App issues - Part 2


## Lab Virtual Machines

The lab environment has two virtual machines.  The first virtual machine hosts the AppDynamics Controller and will be referred to from this point on as the "Controller VM".  

The second virtual machine hosts the Supercar Trader application used in the labs.  It will be the host where you will install the AppDynamics agents and will be referred to from this point on as the "Application VM".

**NOTE:** These will be the same two virtual machines you used in the [Java Application Monitoring Fundamentals Lab](../fnd-01-appd-apm-java/lab-exercise-01.md).

<br>

### Controller VM
![Controller VM Screenshot](./assets/images/01-controller-vm.png)

<br>

### Application VM
![Application VM Screenshot](./assets/images/01-application-vm.png)

<br>

If you are ready to learn how AppDynamics can help you monitor the health of your browser based application, let's get started!   

<br>

[Lab setup](lab-exercise-00.md) | 1, [2](lab-exercise-02.md), [3](lab-exercise-03.md), [4](lab-exercise-04.md), [5](lab-exercise-05.md), [6](lab-exercise-06.md) | [Back](lab-exercise-00.md) | [Next](lab-exercise-02.md)
