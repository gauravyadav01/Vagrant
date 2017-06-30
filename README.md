# Generic Vagrant File

Vagrant file to provision nodes based on yaml file.

# How To's
Create a file servers.yaml in current direcory as follows:

```sh 
---
- name: node1
  ip: 192.168.3.2
```

You can add memeory and cpu with following parameters:
```sh 
---
- name: node1
  ip: 192.168.3.2
  cpu: 2
  memory: 1024
  ```

  Default 1 CPU and 1024 mmeory will get assigned.
