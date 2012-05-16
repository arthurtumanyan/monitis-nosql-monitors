Introduction

riak_monitor.xml is a template for Monitis Monitor Manager. 
It allows to you get some statistic data from Riak via REST API

Install/configure

To make it work you have to install M3 according it's installation rules
In a few steps it can be did like this

1. git clone git@github.com:monitisexchange/Monitis-Linux-Scripts.git
2. cd Monitis-Linux-Scripts/M3
3. change the M3Templates.pm (set your APIKEY & SECRETKEY)
4. run perl Run.pl /path/to/riak/template/riak_monitor.xml

Be sure you have installed MonitisMonitorManager.pm perl module
For detailed information see: Monitis-Linux-Scripts/M3v3/INSTALL.md
