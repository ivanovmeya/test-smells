## Тест одного исхода
Не проверяются все варианты входных данных либо не проверяются все варианты возвращаемых значений.
Легче всего заметить эту проблему для boolean параметров и boolean возвращаемых значений. 

### Проблемы
Проверяется только часть кода.
В тестах не зафиксировано поведение для остальных вариантов.

### Теория
Если тестируемый код может вести себя несколькими способами, то тесты стоит написать на все варианты входных данных.
Если тестируемый код может возвращать несколько вариантов результата, то тесты стоит написать на все варианты результата.

### Что делать
Добавить ещё тестов.