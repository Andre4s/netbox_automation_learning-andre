# NetBox Automation Project

Этот репозиторий - составляющая моих статей по автоматизации. Репозиторий содержит примеры комплексных скриптов по автоматизации Netbox через Python + API. Следуйте этому гайду для настройки и использования.

## Быстрый старт

1. **Установка NetBox**  
Установите NetBox на виртуальную машину, либо следуя [оффициальной документации](https://netbox.readthedocs.io/), либо воспользовавшись [community docker-версией](https://github.com/netbox-community/netbox-docker?tab=readme-ov-file)

2. **Создание API-ключа**  
В интерфейсе NetBox создайте API-ключ с необходимыми правами доступа.

3. **Клонирование репозитория**  
Склонируйте этот репозиторий на вашу локальную машину:  
```bash
git clone <rep>

```
4. **Создание виртуального окружения**
Создайте и активируйте виртуальное окружение:

```python
python -m venv venv
source venv/bin/activate
```

5. **Установка зависимостей**
Установите необходимые библиотеки:

```python
pip install -r requirements.txt
```

6. **Настройка API-ключа и URL NetBox**

В файле config.py укажите:
•	URL вашей установки NetBox.
•	Ваш API-ключ.

7. **Редактирование inventory**
При необходимости измените файл `inventory/inventory.yml` в соответствии с вашими требованиями.

8. **Запуск скрипта**
Запустите основной скрипт с указанием inventory:

```python
python main.py inventory/inventory.yml
```

9.	**???**
10.	**PROFIT!**


Полезное:
- [Документация Netbox-API](https://demo.netbox.dev/api/schema/swagger-ui/)


Если у вас возникнут вопросы, создавайте issue в этом репозитории. Не бойтесь делать это, если вы никогда раньше не контрибьютили. Для прокачивания уверенности рекомендую [How to Contribute to Open Source](https://opensource.guide/how-to-contribute/)

«Don’t use the Force, Luke, try to think!» 🚀
