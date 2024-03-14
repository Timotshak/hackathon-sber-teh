# hackathon-sber-teh

В данном репозитории представлено решение на базе фреймворка SAMPO для кейса СберТех'а на хакатоне It Purple Hack 2024. Данное решение позволяет автоматизировать планирование проектов с помощью эвристик и метаэвристик, реализуя одно-критериальную и мульти-критериальную оптимизацию. 

XML-файлы с результатами на тестовом файле лежат в папке: https://drive.google.com/drive/folders/1B4Ojey6Dti5EWbRkCZ828Y1EPjHjYqlK?usp=sharing

Там представлены результаты оптимизации отдельно по каждому критерию (время, стоимость, ресурсы) и результат усредненной оптимизации с равномерным распределением весов.
Также алгоритм может получать Парето-оптимальные решения, код для запуска различных сценариев оптимизации представлен в файле 'main_pipeline.py'.

Обращаем внимание, что нестандартные даты для задачи "Веха 3" не являются ошибкой, а обусловлены большим временным лагом, указанным в переданном XML-файле (24 000 часов), что учитывается в нашем автоматизированном парсере структуры.

Альтернативное решение от нашей команды - https://github.com/maximdu/notsampo
