# Test task Selenium
### Запуск тестов
Перед запуском указать путь к exe файлу WebDriver хрома вашей версии в src/test/resources/application.properties.<br />
Скачать вебдрайверы хрома версий 114 и ниже - https://chromedriver.chromium.org/downloads<br />
Скачать вебдрайверы хрома версий 115 и выше - https://googlechromelabs.github.io/chrome-for-testing/<br />
Запуск тестов с помощью команды maven - mvn clean test
### Генерация allure отчета
maven - mvn allure:serve
### Тестовое задание Мир квестов
src/test/java/me/umar/TaskTest.java - сам тест с тестовым заданием
