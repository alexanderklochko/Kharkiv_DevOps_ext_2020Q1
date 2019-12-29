ЧАСТЬ 1. РАБОТА С VIRTUALBOX
В этой части задания была создана виртуальна машина, с установленной на ней Ubuntu 16.04 LTS.
Были изучены основные возможности VirtuaBox, например, такие как сохранение состаяния машины (см. рисунок ниже).

![Состояние машины](https://github.com/alexanderklochko/Kharkiv_DevOps_ext_2020Q1/raw/master/task_2.2/im/State_machine.png)

Так же был сделан экспорт виртуальной машыны, который доступен по [ссылке](https://drive.google.com/open?id=1B7vSY7Y920tuRLvOuLXKNYd_4uIFH7m_)
Далее были изучены возможности конфигурирования мишин как через GUI (рисунок ниже):

![Состояние машины](https://github.com/alexanderklochko/Kharkiv_DevOps_ext_2020Q1/raw/master/task_2.2/im/share.png)

так и через CLI

![Создание виртуальной машины](https://github.com/alexanderklochko/Kharkiv_DevOps_ext_2020Q1/raw/master/task_2.2/im/CreateVM.png)

![Выполнение команды showvminfo](https://github.com/alexanderklochko/Kharkiv_DevOps_ext_2020Q1/raw/master/task_2.2/im/showvminfohowvminfo.png)

![Выполнение команды snapshot](https://github.com/alexanderklochko/Kharkiv_DevOps_ext_2020Q1/raw/master/task_2.2/im/take_a_snapshot.png)

![Клонирование машины](https://github.com/alexanderklochko/Kharkiv_DevOps_ext_2020Q1/raw/master/task_2.2/im/createclone.png)

Для созданной машины и её клона было смоделировано несколько сетывых подключений:

![Подключение ВМ к Интернет](https://github.com/alexanderklochko/Kharkiv_DevOps_ext_2020Q1/raw/master/task_2.2/im/VM_1-Internet.png)

![Соединение гостевой и готовых машин](https://github.com/alexanderklochko/Kharkiv_DevOps_ext_2020Q1/raw/master/task_2.2/im/VM_1-Internet-host.png)

![Соединение двух ВМ](https://github.com/alexanderklochko/Kharkiv_DevOps_ext_2020Q1/raw/master/task_2.2/im/VM_1-VM_2.png)

ЧАСТЬ 2. РАБОТА С VAGRANT

В этой части задания был установлен Vagrant, с помощью которого было создано и запущено несколько виртуальных машин, настройки машин были заданы через Vagrantfile, 
скриншот процесса зоздания одной из виртуальных машин приведен ниже:

![Процесс создания виртуальной машмны](https://github.com/alexanderklochko/Kharkiv_DevOps_ext_2020Q1/raw/master/task_2.2/im/working_with_vagrantfile.png)

Далее было выполнено подключение к машине по SSH, для этого использовалась программа Putty, что изображено на рисунке ниже:

![SSH подключение](https://github.com/alexanderklochko/Kharkiv_DevOps_ext_2020Q1/raw/master/task_2.2/im/Connect_vis_SSH.png)

Выключение и удаление машины показано на рисунке ниже:

![Выполнение команд "halt" и "destroy"](https://github.com/alexanderklochko/Kharkiv_DevOps_ext_2020Q1/raw/master/task_2.2/im/halt_and_destroi.png)

В конце задания был создан VagranBox Ubuntu_server_64. Ниже представлен снимок выполнения команды "vagrant box list"

![Список доступных боксов](https://github.com/alexanderklochko/Kharkiv_DevOps_ext_2020Q1/raw/master/task_2.2/im/create_a_box.png)
