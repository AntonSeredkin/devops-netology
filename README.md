# devops-netology
Тестовое изменение для проверки статуса
Для Terraform будут исключены из коммитов такие файлы как:
  1. Логи (файлы с именем crash.log и файлы в имени которых crash. любой набор символов .log)
  2. Локальные директории TF (все файлы во всех директориях .terraform, вложенных в любое количество директорий)
  3. Переменные с чувствиельными данными (креды, секреты) (файлы с любым именем окончивающимся на .tfvars)
  4. Оверрайды (файлы override.tf, override.tf.json и аналогичные с любым "набором символов_" в начале имени)
  5. Настройки CLI (файлы с именами .terraformrc и terraform.rc)

  Остальные строчки закомментированы.
