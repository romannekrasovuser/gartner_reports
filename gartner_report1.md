## Конспект отчёта Гартнер по инструментам для интеграции данных

#### Ссылка на отчёт https://www.gartner.com/doc/reprints?id=1-1OA35PNQ&ct=190715&st=sb&mkt_tok=eyJpIjoiWXpRelpHTmtaRFJpTW1ObSIsInQiOiI0T0doVTZpOGRhVk9nMVhqaE9qQnlhdHpTR2h5eENZRXhOaXpKb0RmM0pQOVVFUk5kYitvYU45RzNtRTBQbTFaNE1VbzhzSjFcLzhKdjNKMlowTUVnRnBcL21rUGY2WWlsMlwvXC9FUDhxajEyRnlvclZPOVpMN1p1TndzTjRmbzloZVcifQ%3D%3D

* Стиль предоставления данных для выполнения задач по их интеграции
* Активные и пассивные метаданные - ключевая разница в том, что пассивные формируются на стадии проектирования хранилища и меняются лишь вручную (описаны в документации или технических метаданных). Активные могут изменяться с течением времени и адаптированы под методы машинного обучения
* Цель в автоматизации проектирования интеграции данных и построения инфраструктуры (либо рекомендательной системы)
* Оптимизированная и воспроизводимая аналитика
* Сценарии интеграции данных:
** Оптимизированная аналитика
** Доставка данных для MDM-систем
** Согласованность данных между операциионными приложениями
** Сбор и обмен данными об организации с заинтересованными лицами
** Оркестрация дата-сервисов
** Миграция данных и их консолидация
** Поддержка управления данными (сбор, аудит, обмен, мониторинг, способность признать сходный характер данных)
* Данные как актив
* NoSQL - Hadoop, нереляционные базы, облачные хранилища
* Аналитические репозитории управления данными
* 3 типа нереляционных баз данных - хранилища ключевых значений, графические базы, базы документов
* Современные стили интеграции - виртуализация данных, подготовка и интеграция потоковых данных
* Компания Actian - продукт DataConnect (простота, только пакетная аналитика)
* Adeptia - Adeptia Connect (для гибридных платформ, слабость в управлении метаданными)
* Denodo - Denodo Platform (виртуализация данных, логическая абстракция при объединении данных, проблемы с универсальностью при стыковке виртуализации с другими стилями доставки данных - групповые и пакетные ETL, дорого)
* Hitachi Vantara - Pentaho Data Integration, Hitachi Streaming Data Platform (HSDP) и Hitachi Data Instance Director (HDID) (стали делать упор на интернет вещей, синергия инструментов интеграции с набором технологий по управлению данными, нет признания дата-сообществом)
* IBM -  IBM InfoSphere Information Server, IBM InfoSphere Classic Federation Server, IBM InfoSphere Data Replication, IBM App Connect, IBM Streams и IBM Data Refinery (самая крупная 11 тыс. клиентов-организаций, богатый функционал, поддержка различных стилей интеграции данных как современных, так и традиционных - репликация, пакетная обработка, синхронизация и интеграция потоковых данных, бренд, слабый стиль виртуализации данных, недостаточная поддержка межоблачной интеграции, дорого, сложность обновления инструментов)
* Informatica - PowerCenter, PowerExchange, Data Replication, B2B Data Transformation, B2B Data Exchange, Data Integration Hub, Data Services, Intelligent Cloud Services, Big Data Management, Big Data Integration Hub, Big Data Streaming, Enterprise Data Catalog, Enterprise Data Preparation и Edge Data Streaming, 10 тыс. клиентов - (пилят движок CLAIRE - автоматизация интеграции, включая обнаружение метаданных, каталогизация, линейный анализ, анализ влияния, рекомендации на основе AI, развитый функционал поддержки гибридных, облачных и многооблачных хранилищ, активно увеличивают долю рынка, развитая партнерская сеть, дорого)
* Information Builder - Omni-Gen data integration platform, iWay Service Manager, iWay DataMigrator и iWay Universal Adapter Suite (интеграция с MDM и инструмента управления качеством, слабые управление метаданными и функционал моделирования)
* Microsoft - SQL Server Integration Services (SSIS), Azure Data Factory (ADF) - (низкая стоимость владения, простота, гибридная интеграция, универсальность платформы, сложность миграции, негативные отзывы по работе с метаданными и моделированием, включая активные метаданные)
* Oracle - Oracle Data Integration Platform Cloud Service включая Oracle GoldenGate Cloud Service и Oracle Data Integrator Cloud Service), Oracle GoldenGate, Oracle Data Integrator (ODI), Oracle Big Data SQL, Oracle Service Bus и Oracle Integration Cloud Service, 12 тыс. клиентов - обширные сценарии репликации и интеграции потоковых данных, распределенные https и RESTful API, поддержка Kafka, Spark, дорого, клиенты слабо знают о современных сценариях интеграции (гибридная, активные метаданные, используют лишь групповую, пакетную интеграцию)
* Qlik (Attunity) - Attunity Replicate, Attunity Compose, Attunity Visibility и Attunity Enterprise Manager, 2500 клиентов (простота, надежная репликация, автоматическая генерация кода, отсутствие поддержки стилей интеграции, отличающихся от репликации/синхронизации)
* SAP - лидер рынка по числу организаций, 60 тыс., SAP Data Services, SAP Replication Server, SAP Landscape Transformation Replication Server, SAP Data Hub, SAP HANA и SAP Cloud Platform Integration Suite. SAP HANA platform включает SAP HANA Smart Data Integration (для групповой/пакетной и низкочастотной доставки данных), SAP HANA Smart Data Access (виртуализации данных) и SAP HANA Streaming Analytics (аналитика потоковых данных) - широкий функционал, активные метаданные, единая среда, развитая экосреда и партнерская сеть, дорого и сложность администрирования
* SAS - SAS Data Management, SAS Data Integration Studio, SAS Federation Server, SAS/ACCESS, SAS Data Loader для Hadoop, SAS Data Preparation и SAS Event Stream Processing, 14 тыс. организаций, опенсорсный проект по управлению метаданными с ODPi Egeria, активные метаданные, машинное обучение в метаданных, хороший послепродажный сервис, отдельное место подготовке данных SAS Data Preparation, дорого, сложность развертывания
* SnapLogic - SnapLogic Intelligent Integration Platform - очень богатые возможности интеграции данных, свыше 500 коннекторов, низкая цена, есть триальная версия, качество документации, устаревший интерфейс
* Syncsort - Syncsort Connect (высокая производительность ETL и низкая стоимость владения, не хватает функционала по управлению метаданными)
* Talend - Talend Open Studio, Talend Data Fabric, Talend Data Management Platform, Talend Big Data Platform, Talend Data Services Platform, Talend Integration Cloud и Talend Stitch Data Loader (хорошая платформа для гибридной и многооблачной интеграции, сообщество, поддержка опенсорсных технологий Apache Beam, Spark и Kafka, растущие цены, онлайн-документация, миграция и модернизация, проблемы с партнерской сетью)
* TIBCO Software - TIBCO Data Virtualization (TDV), TIBCO Cloud Integration, TIBCO EBX, TIBCO StreamBase, TIBCO Messaging и TIBCO Spotfire. TIBCO Messaging включает TIBCO FTL, TIBCO eFTL, TIBCO Flogo Enterprise and TIBCO Enterprise Message Service (широкая поддержка традиционных и перспективных стилей доставки данных, динамическое распределение большого объема данных среди множества процессов с помощью Apache Drill, поддержка Elasticsearch, хорошие возможности интеграции потоковых данных и очередей брокеров сообщений, сильная виртуализация данных, дефицит специалистов по продукты, слабая комплескная поддержка традиционных стилей доставки данных с пакетной аналитикой)



