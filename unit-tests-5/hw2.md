﻿Давайте разберем каждый из представленных тестовых сценариев и определим их тип:

1. **Проверка того, что функция addContact корректно добавляет новый контакт в список контактов**:
   - **Тип теста:** Юнит-тест.
   - **Объяснение:** Этот тест проверяет только отдельную функцию `addContact`, изолированную от других компонентов приложения. Он не взаимодействует с внешними зависимостями или ресурсами, такими как база данных или пользовательский интерфейс, и проверяет только корректность работы этой функции.

2. **Проверка того, что при добавлении контакта через пользовательский интерфейс, контакт корректно отображается в списке контактов**:
   - **Тип теста:** Сквозной тест.
   - **Объяснение:** Этот тест проверяет весь путь данных от пользовательского интерфейса до списка контактов. Он включает в себя как пользовательский интерфейс, так и внутренние функции, связанные с добавлением контакта в список. Такой тест называется сквозным, потому что он охватывает несколько компонентов приложения и проверяет, что они работают вместе корректно.

3. **Проверка полного цикла работы с контактом: создание контакта, его редактирование и последующее удаление**:
   - **Тип теста:** Интеграционный тест.
   - **Объяснение:** Этот тест проверяет взаимодействие нескольких компонентов приложения, таких как создание, редактирование и удаление контакта. Он включает в себя как внутренние функции приложения, так и внешние ресурсы, такие как база данных. Такой тест называется интеграционным, потому что он проверяет, как различные компоненты интегрируются и работают вместе в рамках одного целого.