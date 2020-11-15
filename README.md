# stand_01_lvm
Добавим инсталяцию lvm2 и xfsdump в Vagrantfile
yum install -y mdadm smartmontools hdparm gdisk lvm2 xfsdump

Создадим директорию для файлов утилиты scripts
mkdir /tmp/scripts

Запустим утилиту scripts
scripts -t5 -a /tmp/scripts/session01
