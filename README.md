# Linux Server Configuration

### Overview

This is the fifth project of Udacity's [Full-stack Web Developer Nanodegree](https://www.udacity.com/course/nd004).  The base repository is located at [udacity-full-stack](https://github.com/allanbreyes/udacity-full-stack).  This project takes a baseline installation of a Linux distribution on a virtual machine and prepares it to host a web application by installing updates, securing it from a number of attack vectors, and installing/configuring web and database servers.

### HTTP

The web application, [The MOOC Catalog](https://github.com/allanbreyes/mooc-catalog), is hosted via HTTP at the server's IP address: [52.10.171.172](http://52.10.171.172/).

### SSH

To gain entry into the server, one can SSH into the server by executing the command:

```
ssh -p 2200 -i [RSA_FILE] grader@52.10.171.172
```

*Note: the SSH port is `2200`.  Additionally, please ensure the RSA file (private key) is included and the correct password is entered upon login.