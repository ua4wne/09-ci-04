## Подготовка к выполнению

1. Создать две VM: для jenkins-master и jenkins-agent.

![vm](./task1/vm.png)

2. Установить Jenkins при помощи playbook.

![deploy](./task1/deploy.png)

3. Запустить и проверить работоспособность.

![step1](./task1/step1.png)
![step2](./task1/step2.png)
![step3](./task1/step3.png)
![finish](./task1/finish.png)

4. Сделать первоначальную настройку.

![agents](./task1/agents.png)

## Основная часть

1. Сделать Freestyle Job, который будет запускать molecule test из любого вашего репозитория с ролью.

![fstyle1](./task2/fstyle1.png)
![fstyle2](./task2/fstyle2.png)
![fstyle3](./task2/fstyle3.png)
![console1](./task2/console1.png)
![console2](./task2/console2.png)
![result](./task2/result.png)

2. Сделать Declarative Pipeline Job, который будет запускать molecule test из любого вашего репозитория с ролью.

![settings1](./task3/settings1.png)
![settings2](./task3/settings2.png)
![console1](./task3/console1.png)
![console2](./task3/console2.png)
![result](./task3/result.png)

3. Перенести Declarative Pipeline в репозиторий в файл Jenkinsfile.

>Ответ: [Jenkinsfile](./Jenkinsfile)

4. Создать Multibranch Pipeline на запуск Jenkinsfile из репозитория.

