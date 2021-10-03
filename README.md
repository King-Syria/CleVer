# Bot `CleVer`

welcome !

* Bot `clever` works with the Ejabberd system

## Requirements:

* Linux x86_64 server Ubuntu up 14

* You must install the following programs:

### install python 2.7

``` bash
  $ apt-get install python 2
```

### install zope.interface 5.4.0

``` bash
  $ pip2 install zope.interface==5.4.0
```

### install termcolor 1.1.0

``` bash
  $ pip2 install termcolor==1.1.0
```

### install Twisted 13.0.0

``` bash
  $ pip2 install Twisted==13.0.0
```

## Then modify the settings file:

* Edit a_settings.py

``` python

Setting = {
'JidBot': 'clever@service.com',
'PassBot': '****',
'ResBot': 'Bot',
'NickBot': u'-1',
'ShowBot': 'dnd',
'StatusBot': 'http://service.com/ \nBOT CLEVER \nking-syria@service.com ',
'RoomBot': u'clever@conference.service.com',
'JidIp': 'king-syria@service.com'}
AdminBot = u'king-syria@service.com',u''


```
Edit other.py

``` python

#The length of the message to split#
Msg_limit_ = 1000

#View the newscast#
News_="no"#yes , no

#News bulletin time#
TNews_=7200

#Reboot timing#
Time_Res_=7200

#Some commands will be disabled to speed up the work of the bot#
#Make the bot special for filtering just type yes to activate the rest of the commands type no#
Log_NJRVM_="yes"#yes , no

#The smallest nickname length#
Max_nick_small_ = 3

#The largest nickname length#
Max_nick_big_ = 32

#The smallest res length#
Max_res_small_ = 3

#The largest res length#
Max_res_big_ = 42

#smallest prs length#
Max_status_small_ = 1

#The largest prs length#
Max_status_big_ = 600

#The smallest message length#
Max_msg_small_ = 1

#The largest message length#
Max_msg_big_ = 600

#Message speed time#
Time_Msg_ = 1.8

#bot special protection#
#Giving orders in private#
Comand_Private_ = "on"#off [to disable commands in private off] or on [to activate commands through private on]#

#The least access is allowed to speak in the private bot#
Access_Comand_Private_ = 20


```
## Then run the bot file:

``` python
  python2 ./clever.py
```

## For help, add:

king-syria@syriatalk.org (main account)

~ That's it, thank you

# © By `KinG-SyRia`
