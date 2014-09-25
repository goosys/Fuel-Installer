#FuelPHP Quick Installer

* Version: 1.0

### Information

### Usage

* Create a project directory. (ex. /PROJECT)
* Download composer.json in this directory
* curl -s http://getcomposer.org/installer | php
* php composer.phar install
* wget https://raw.githubusercontent.com/fuel/fuel/352f83a9e23d02145c38a6f93c50b6fe08a02b07/oil -O oil --no-check-certificate

※1.8とmergeしたoilではautoloadの扱いが異なるため、merge前のoilをダウンロードする

### Result
* Fuel/Core is installed
* Some basic packages(auth,oil,orm,email,parser) is installed
* [Empty directories](https://github.com/goosys/Fuel-Vendor-Enptyapp) in fuel/app is created
* Git is initialized for your application
* Let's start to build your application!
