
# Требуется создать программу, выполняющую следующие действия:
1. Создание процесса-потомка
Далее действия программы в процессе-родителе и процессе-потомке описываются отдельно.

# Действия программы в процессе-родителе
2. Вывести сообщение о том, что программа выполняется в родителе. В текст сообщения должна
   быть включена информация о PID родительского (т.е. текущего) процесса и PID процесса-потомка.
3. Дождаться завершения процеса-потомка.
4. Вывести сообщение о завершении процесса-потомка и его код завершения.

# Действия программы в процессе-потомке
2. Вывести сообщение о том, что программа выполняется в процессе-потомке. В текст сообщения должна
   быть включена информация о PID процесса-потомка (т.е. текущего процесса) и PID процесса-родителя.
3. Запустить на выполнение следующую командную строку:
   /bin/ls -la /tmp
   
# Дополнительные требования
1. В программе должны использоваться вызовы функций fork(),exec*(),wait(),exit().
2. В программе должны использоваться макросы WIFEXITED(), WEXITSTATUS().
3. Вызовы функций должны сопровождаться проверкой возвращаемых значений.


