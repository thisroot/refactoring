## Введение

Рефакторинг - процесс изменнения программной системы, в ходе которого внешнее поведение остается
неизменным при усовершенствовании его внутренней структуры

#### Принципы рефакторинга
- Совершенствует проектирование программного обеспечения
    - позволяет поддерживать комфортный уровень структурированности
    - устраняет дублирование кода
    - Высокий уровень общей применимости функций
- Упрощает понимание программ
- Упрощает поиск ошибок
- Ускоряет нписание программ

#### Классификация рефакторингов
- Подготовительный рефакторинг - проводится непосредственно в процессе разработки
программного обеспечения
- Осмыслительный рефакторинг - предварительная фаза при изучении кода, ребуется для определения 
границ рефакторига в контексте изучаемой кодовой базы
    - Убирающий рефакторинг - вариация осмыслительного - опирается на возможности упрощения
    реализации путем удаления, группировки функций
- Запланированный и спонтанный рефакторинг - может быть запланированным, а может быть привязан
к существующему циклу разработки
- Долгосрочный рефакторинг - рефакторинг требующий существенной переработки программого обеспечения,
с большими временными затратами.
 - Может быть постепенным (в случае применимости), по мере работы над развитием ПО применение требований рефакторинга к
 затрагиваемым участкам кодовой базы
 - Рефакторинг в ходе анализа кода - может быть привязан к код-ревью
 
 #### Проблемы при рефакторинге
 - Замеделение введения новых возможностей
 - Владение кодом - ограничивается возможностями рефакторинга кодовой базы (внешние модули, закрытые API, проприетарное ПО)
 - Системы контроля версий ( проблемы слияния ветвей )
 - Тестирование ( наличие самотестируемого кода )
 - Устаревший код
 - Базы данных