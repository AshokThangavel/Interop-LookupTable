# Interop-LookupTable
InterSystems IRIS interoperability Lookup table UI    
<img src="https://community.intersystems.com/sites/default/files/inline/images/images/image(12015).png"></img>    
### Prerequisites
Make sure you have [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) and [Docker desktop](https://www.docker.com/products/docker-desktop) installed.
### Installation
Clone/git pull the repo into any local directory   
```
$ git clone https://github.com/AshokThangavel/Interop-LookupTable.git   
```
To build the container run:   
```
$ docker compose --progress plain build
```
To start the container run:     
```
$ docker compose up -d && docker compose logs -f
```
To access IRIS System Management Portal    
http://localhost:52773/csp/sys/UtilHome.csp
### How to use it
The demo starts with this URL    
http://localhost:52773/csp/user/Interop.LookUpTable.cls

```
