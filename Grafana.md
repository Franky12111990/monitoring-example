Задание 1
Используя директорию help внутри этого домашнего задания, запустите связку prometheus-grafana.
Зайдите в веб-интерфейс grafana, используя авторизационные данные, указанные в манифесте docker-compose.
Подключите поднятый вами prometheus, как источник данных.
Решение домашнего задания — скриншот веб-интерфейса grafana со списком подключенных Datasource.

Решение:
<img width="923" alt="image" src="https://github.com/user-attachments/assets/6b0ee7e7-b13e-4f17-910b-5bed3edd511c">


Задание 2
Изучите самостоятельно ресурсы:

PromQL tutorial for beginners and humans.
Understanding Machine CPU usage.
Introduction to PromQL, the Prometheus query language.
Создайте Dashboard и в ней создайте Panels:

утилизация CPU для nodeexporter (в процентах, 100-idle);
CPULA 1/5/15;
количество свободной оперативной памяти;
количество места на файловой системе.
Для решения этого задания приведите promql-запросы для выдачи этих метрик, а также скриншот получившейся Dashboard.

Решение:
<img width="869" alt="image" src="https://github.com/user-attachments/assets/ea947f01-c527-4eb9-8c67-885c746904b1">

<img width="911" alt="image" src="https://github.com/user-attachments/assets/2fe81b18-7330-404b-b1c6-9fcbcfb91e81">

<img width="741" alt="image" src="https://github.com/user-attachments/assets/1790155d-a76b-47f5-93b4-461725e0b322">

<img width="751" alt="image" src="https://github.com/user-attachments/assets/59ca53c7-c182-442c-a358-8f55a1ef8cec">

<img width="925" alt="image" src="https://github.com/user-attachments/assets/9bac51ef-bce9-4f18-9077-172011899d15">

Задание 3
Создайте для каждой Dashboard подходящее правило alert — можно обратиться к первой лекции в блоке «Мониторинг».
В качестве решения задания приведите скриншот вашей итоговой Dashboard.
Решение
<img width="932" alt="image" src="https://github.com/user-attachments/assets/769ba4b0-fecb-4d19-8221-d2679d2e0d5d">

Задание 4
Сохраните ваш Dashboard.Для этого перейдите в настройки Dashboard, выберите в боковом меню «JSON MODEL». Далее скопируйте отображаемое json-содержимое в отдельный файл и сохраните его.
В качестве решения задания приведите листинг этого файла.
Решение
<img width="653" alt="image" src="https://github.com/user-attachments/assets/b1720e40-aa7e-4741-badd-2fe4e59901bd">
