# SUMMER HOMEWORK

## Введение
В качестве выборки в рамках домашнего задания по курсу DSIS была выбрана `Cybersecurity Risk (2022 CISA Vulnerability)`, (URL: https://www.kaggle.com/datasets/thedevastator/exploring-cybersecurity-risk-via-2022-cisa-vulne). (Файл `databases.zip`) 

Данная выборка содержит информацию об эксплуатируемых уязвимостях из каталога CISA, включаю информацию о `CVE ID`, `vendor project`, `product`, `vulnerability name`, `date added`, `short description`, `required action`, `due date`, `notes`, `group`, `publication date`, `CVSS store`, `CWE`, `vector`, `complexity`, `severity`.

Необходимо исследовать данную выборку, построить различные графики и разрезы.

## Ход работы 

В качестве библиотеки для анализа данных используется `pandas`. В качестве инструментов визуализации используется `matplotlib`, `seaborn`. 

В первую очередь были построены графики, отражающие кол-ва уязвимостей по их серьёзности и сложности. Далее диаграмма, показывающая процентное соотношение продуктов по кол-ву уязвимостей и количественная диаграмма CVSS. Затем были проанализированы наиболее опасные сетевые уязвимости (cvss = 10.0). По этим данным был построен график "Дата публикации сетевых уязвимостей со значением cvss равным 10.0 разными компаниями". 

## Заключение 

Были проанализрованы данные. Сделаны выводы по кол-ву серьёзных уязвимостей, компаниям, предоставляющие потенциально наиболее опасные сервисы и продукты. Выявлены опасные сетевые уязвимости. Были применены умения работы с библиотеками по визуализациям данных и их анализу.
