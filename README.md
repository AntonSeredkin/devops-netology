# devops-netology
Домашнее задание по лекции "Работа в терминале (лекция 1)"
5) 2 vCPU, 1024MB RAM, 64GB HDD
6) config.vm.provider "virtualbox" do |vb|
          vb.cpus = 4
          vb.memory = 2048
   end
8) - history-size, line 2399
   - ignoreboth - не хранить в истории строки начинающиеся с пробела и дублирующиеся команды
9) {} используются в скриптах для определения списков, первое упоминание строка 179, раскрывается суть - 257
10) touch {1..10000}, 300000 создать нельзя Argument list too long
11) [[ -d /tmp ]] вернет True, если /tmp - директория
12) mkdir /tmp/new_path_directory
    cp /bin/bash /tmp/new_path_directory 
    export PATH=/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/usr/games:/usr/local/games:/snap/bin:/tmp/new_path_directory
13) at выполнит команду в заданное время, batch выполнит когда средняя загрузка системы будет <1,5
