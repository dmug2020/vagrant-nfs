# Д.З 32

Vagrant стенд для NFS или SAMBA
NFS или SAMBA на выбор:

vagrant up должен поднимать 2 виртуалки: сервер и клиент
на сервер должна быть расшарена директория
на клиента она должна автоматически монтироваться при старте (fstab или autofs)
в шаре должна быть папка upload с правами на запись
- требования для NFS: NFSv3 по UDP, включенный firewall

В Д.З 
Вагрант файл https://github.com/dmirty/32/blob/master/Vagrantfile 
и роли серера и клиента nfs  а также скриншот
https://github.com/dmirty/32/blob/master/iMG.JPG


