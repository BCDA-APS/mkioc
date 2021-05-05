# mkioc
GitLab IOC Generation Script

## Usage

```
$ ./mkioc -h
Usage: mkioc [options] ioc_name

-h            print this message
-v            print the version
-f            create a fresh git repo without an xxx remote
-g            default to creating gitlab repo and pushing ioc
-n            default to not creating gitlab repo and pushing ioc
-s <version>  use a specific synApps version
```

## How to create an IOC similar to makeIOC.sh

```
$ ./mkioc -f -n 
```

