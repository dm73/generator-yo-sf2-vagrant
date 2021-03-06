# Prject Name

Project access points.

  - Production : [prject.ltd] [prject.ltd] 
  - Staging :  [prject.company.ltd] [prject.company.ltd] 
  - local : [prject.dev] [prject.dev] 

### Contributors
Project Manager :  [full name] [@author]<br>
Frontend Developers : [full name] [@author] <br>
Backend Developers : [full name] [@author] <br>
Readme Author : [full name] [@author] 

### Version
1.0.0

### Tech

[prject] uses a number of open source projects to work properly:

* [Twitter Bootstrap 3] - great UI boilerplate for modern web apps
* [Gulp] - the streaming build system
* [jQuery] - duh
* [composer]  Dependency Manager for PHP
* [bower] A package manager for the web
* [compass] Compass is an open-source CSS Authoring Framework.
* [symfony 2]  PHP framework for web projects 

### Installation instructions

You need vagrant installed:

```sh
$ git clone [git link]
$ cd [prject]
$ vagrant up
```
Connect to VM [SSH]
```sh
$ vagrant ssh
$ cd /var/www/[prject]
```

### Frontend Development

Want to contribute? Great!

Planet-test use gulp for fast developing.
Open your favorite Terminal connect project machine via ssh and run these commands.

Build desktop assets : */var/www/[prject]/app/Resources/scss/desktop*
```sh
$ gulp 
```


### Backend Development

Want to contribute? Great!

[prject] use sf2 as framework.
Open your favorite Terminal connect project machine via ssh and run these commands.

configure your project includeed in composer
```sh
$ php composer.phar install 
```
for vagrant users just tape ** Enter ** <br>
for other sf command  refer to http://symfony.com/ 
```sh
$ php app/console  
```

### deployement 

Want to deploy ? Congratulations :)

##### In staging Server (Test) 
add these var to vhost. <br>
```sh
APP_ENV dev
ENV_SF_ENV test
```

##### In Prod Server 
add these var to vhost. <br>
```sh
ENV_SF_ENV prod
```


### Todo's

 - Write Tests
 - Rethink Documentation
 - Add Code Comments

### ChangeLog


**Undocumented Software, Hell Yeah!**

[prject.ltd]:http://prject.ltd/
[prject.company.ltd]:http://prject.company.ltd/
[prject.dev]:http://prject.dev/
[@author]:mailto:author@company.ltd

###### This template generated by [yo-sf2-vagrant] [yo-sf2-vagrant]
[yo-sf2-vagrant]: https://www.npmjs.com/package/generator-yo-sf2-vagrant 
