
#### REFERENCES

- Have a look at below source code(s):
  - https://github.com/hashicorp/nomad/tree/master/client/driver
  - https://github.com/containernetworking/cni

#### NOTE

- cni show cases below features:
  - makes itself available for import by other libs.
  - enables developers to follow a **template code** to create cni plugins
  - provides a cli
- cni is a `kiss` interface between container execution & network plugin
- cni is good for anyone wanting to create a container networking project
