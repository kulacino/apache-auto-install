# apache-auto-install
ApacheAutoInstall is a simple bash script to update and install various apache stack from ppa source.

## Getting Started

These instructions will get you a simple step to run this bash script. In this bash script, you could install two different apache stacks. You could install Apache 2.x with PHP-FPM 5 or PHP-FPM 7.

### System Requirements
Here are some system requirements to avoid error when using the script. Please make sure to read this before ask something about the error messages.

- Chmod your script into executable files.
```
$ sudo chmod +x ApacheAutoInstall.sh
```
or
```
$ sudo chmod 755 ApacheAutoInstall.sh
```

- Script need to be run as root user or using sudo.
```
$ sudo ./ApacheAutoInstall.sh
```
or
```
# ./ApacheAuthoInstall.sh (this # means you are root user)
```

### Installation
The script need your specified $1, since it's using condition to install your needed packages.
- Define the script followed by php5 which will install apache2 and php5.6 stack to your system.
```
$ ./ApacheAutoInstall.sh php5
```
- Define the script followed by php7 which will install apache2 and php7.0.x stack to your system. 
```
$ ./ApacheAutoInstall.sh php7 
```

## Versioning

This first script was v1.0. For the versions available, see the [tags on this repository](https://github.com/cynthiayu/apache-auto-install/tags). 

## Authors

* **Cynthia Ayu Windani** - *Initial work* - [cynthiayu](https://github.com/cynthiayu)

## License

This project is licensed under the GNU GPL-3.0 - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments

* **Billie Thompson** from [PurpleBooth](https://github.com/PurpleBooth) for Readme-Template.
* **Nicolas Hennion** from [nicolargo](https://github.com/nicolargo) for well structured if-else condition.
