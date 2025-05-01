# Introduction to Ansible

## What is Ansible ?
Ansible -

Ansible is the open source IT configuration management, Deployment and Orchestration tool.
it aims to provide the large productivity gain to a wide variety of automation challenges.
Ansible is available in various flavour of linux - centos, ubuntu, centos, Debian.
we can use ansible weather our servers are in on-primises or cloud machines

Advantage -

easy to use

free to use

light in weight

secure because of agentless compatibility

does not need any special system administrator skill to install and use it.

works on push mechanism


Disadvantage

it is not fully Automated

limited support because i think it new in the market.

Ansible tower is GUI, but it is still in development stages.



Ansible is an open source IT automation engine that automates 
- provisioning
- configuration management
- application deployment
- orchestration

and many other IT processes. It is free to use, and the project benefits from the experience and intelligence of its thousands of contributors.

## How Ansible works ?

Ansible is agentless in nature, which means you don't need install any software on the manage nodes.

For automating Linux and Windows, Ansible connects to managed nodes and pushes out small programs—called Ansible modules—to them. These programs are written to be resource models of the desired state of the system. Ansible then executes these modules (over SSH by default), and removes them when finished. These modules are designed to be idempotent when possible, so that they only make changes to a system when necessary.

For automating network devices and other IT appliances where modules cannot be executed, Ansible runs on the control node. Since Ansible is agentless, it can still communicate with devices without requiring an application or service to be installed on the managed node.



