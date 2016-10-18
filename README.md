ipython notebook for docker 
====

Kaggle Competation using by the iython notebook and pandas

## Description
This is the making tool for the elasticsearch

If you see the detail about it, you see the below<br>


#
### Install

Vagrant

https://www.vagrantup.com/

#
### Usage
#

#### making enviroment for docker

```
cd provisioning
ansible-playbook -vvvv -i hosts site.yml
```

#### making docker container for elastic search

```
cd docker
make test-elastic-search
```

#### Start ipython notebook

```
sh elastic_search_setting.sh
```


#
### Code Directory Structure
#
```
ELasticsearch and docker container
  - docker/　　　　　... Docker tool
    - conf/　　　　　... setting conf file
    - data/　　　　　... regist test data
    - dockerfiles/　　　　　... Docker file for making enviroments
    - elastic-search-python/　　... python script
    - shell/　　... start the elasticsearch and set the documents for elastisearch
    - template/　　... template file for elastisearch
  - provisioning/　     　... Ansible tools
```
#
### Licence
#
```
The MIT License (MIT)

Copyright (c) 2015 Masaya Ogushi

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
```
#
### Author
#
[SnowMasaya](https://github.com/SnowMasaya)
### References
#
>[Docker](https://www.docker.com/)<br>
>[docker-project-template](https://github.com/ahawkins/docker-project-template)
