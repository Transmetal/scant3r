<h1 align="center">
  <br>
  <br>
  ScanT3r
  <br>  
</h1>

***

### Description
scant3r is a module-based web security tool, our goal is to make customizable tool with providing many functions and features that what you need for write a security module for an example (cookie parser/http request class/opts parsing etc ..) to make write a security module easy and simple for saving your time also we made it customizable as possible for example you can change what you want for example options parser you can change/add more options by a config file and scanning map content_types help message logos etc ...

### How can I benefit from this project?
* for bug bounty hunters : <br>
you can use it with the main modules in the table below or write your own module
* for developers : <br>
you can read the source code and try to understand how to make a project like this, or you can get all functions of scant3r in your projects (based on) and try to add more features with scant3r team support :D


### Modules

this the modules we providing for our community for you need new module open an issue with `Feature request
` template or write your own module ;D 

| module         | Short description                                           |
| :------------- | :-------------                                               |
| **lorsrf**     | Bruteforcing on Hidden parameters to find SSRF vulnerability |
| **ssrf**       | simple ssrf scanner                                          |
| **cve**        | cve checks module wtih python scripts and YAML template      |
| **firebase**   | checks for public firebase database (write/read) permission  |
| **paths**      | checking for custom paths                                    |
| **xss**        | inject xss payload in parameter value                        |
| **sqli**       | simple sqli scanner                                          |
| **rce**        | simple RCE scanner
| **xss_param** | inject xss payload in parameter name
| **ssti** | simple server side template injection scanner |
| **exec** | run multi tasks for automate your work/recon |
| **injheaders** | inject blind xss and custom payloads in custom headers (headers.yaml&payload.yaml)
| **reflect** | find reflected parameters 
| **secrets** | find interesting variables content (API Keys , Debug Mode , etc ..) |

#### Requirements
* python >= 3.6
* pip
* Git

#### install
* Unix & MS-DOS

```bash
$ git clone https://github.com/Transmetal/scant3r
$ cd scant3r
$ pip3 install -r requirements.txt
$ ./scant3r.py -h
```
