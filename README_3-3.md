# Домашнее задание к занятию "3.3. Операционные системы, лекция 1"
-------
1. chdir("/tmp")
2. /usr/share/misc/magic.mgc
3. sudo cp /dev/null  /proc/[PID]/fd/[FD]
4. Процессы-зомби не занимают системные ресурсы, т.к. окончили свое исполнение
5. ```
    vagrant@vagrant:~$ sudo opensnoop-bpfcc
    PID    COMM               FD ERR PATH
    830    vminfo              5   0 /var/run/utmp
    619    dbus-daemon        -1   2 /usr/local/share/dbus-1/system-services
    619    dbus-daemon        20   0 /usr/share/dbus-1/system-services
    619    dbus-daemon        -1   2 /lib/dbus-1/system-services
    619    dbus-daemon        20   0 /var/lib/snapd/dbus-1/system-services/
    ```
6. uname().  Part of the utsname information is also accessible via /proc/sys/kernel/{ostype, hostname, osrelease, version, domainname}.
7. При использовании ; следующая за ; команда будет выполнена независимо от результата выполнения предыдущей команды. При использовании && следующая команда будет выполнена только при успешном выполнении предыдущей. При установке set -e команда, как часть && будет выполнена несмотря на результат исполнения предыдущей.
8. Ознакомился с https://gist.github.com/mohanpedala/1e2ff5661761d3abd0385e8223e16425
9. Самый частый статус S - interruptible sleep (waiting for an event to complete)