

# Отчёт о тестировании <Руководство использования KeyValidator>

## Приложение KeyValidator распространяется в виде файла KeyValidator.class, предназначенного для работы на платформе Java 8+.

* 04.03.2021 - 05.03.2021> было проведено динамическое тестирование приложения <KeyValidator>.

* На тестирование затрачено: 17 часов.

В результате тестирования выявлены следующие дефекты:

* <Запуск приложения <Руководство использования KeyValidator> валидным ключом  387eedc6-12e9-3b32-9881-63b6b5e85317 вызывает ошибку “FAIL”.
https://docs.google.com/document/d/1JzPRr7FCGjpkC4pGQuk2w9nH7Xkj0J9ukRpyx_E1ao8/edit?usp=sharing>
* <Запуск приложения <Руководство использования KeyValidator> валидным ключом  80b427f8-92cd-3aae-ba04-03927fbe17c6 вызывает ошибку “FAIL”
https://docs.google.com/document/d/1JzPRr7FCGjpkC4pGQuk2w9nH7Xkj0J9ukRpyx_E1ao8/edit?usp=sharing>


## В процессе тестирования осуществлялись "Запуск приложения <Руководство использования KeyValidator> верными (валидными) и невалидными параметрами 

В процессе тестирования использовались следующие артефакты*:

* Тест кейс: https://drive.google.com/file/d/1mSsPxog-a_3TGJ5KuCaTUkxk5fh753_J/view?usp=sharing



В качестве тестовых данных использовались данные:
 * 1.Удаленный репозиторий по ссылке <https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md>.
 * 2. файл KeyValidator.class
 * 3. Ключи для проверки из данного файла

* Ожидаемый результат: Result for 80b427f8-92cd-3aae-ba04-03927fbe17c6: ОК
* Ожидаемый результат: Result for 387eedc6-12e9-3b32-9881-63b6b5e85317: ОК

Тестирование производилось в следующем окружении:

* "Windows 10 домашняя верси 1909 сборка ОС 18363.1379"
* "openjdk version "11.0.10" 2021-01-19
OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.10+9)
OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.10+9, mixed mode>
