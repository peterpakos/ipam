# ipam
IP Address Manager (NIPAP Client)

## Python modules
Run the following command to install required Python modules:
~~~
$ pip install -r requirements.txt
~~~

## Configuration
Edit and save the sample config file `CONFIG_SAMPLE.py` as `CONFIG.py`.

## Usage
```
$ ./ipam --help
usage: ipam [--version] [--help] {vrf,prefix,search} ...

IP Address Manager (NIPAP Client)

optional arguments:
  --version            show program's version number and exit
  --help               show this help message and exit

commands:
  {vrf,prefix,search}
    vrf                manage VRFs
    prefix             manage prefixes
    search             search prefixes (shortcut for "prefix search")
```
