# Разделение ответственности. Часть 1

Это упражнение продемонстрирует принцип Разделения Ответственности. Наш файл `vendingMachine.js`, такой большой и содержит так много функций. Чтобы сделать наш код проще и более поддерживаемым, мы сгруппируем функции в свои файлы. 

Чтобы выполнить упражнение, возьмите 4 метода и несколько переменных, которые относятся к управлению балансом и переместите их в `balanceManager.js`. Затем вернитесь в `vendingMachine.js` и замените способ вызова этих функций с `this` на наш новый `balanceManager`.

Всё верно! Переместите 4 метода, убедитесь что они вызываются с помощью `balanceManager`, запустите тесты, и у нас будет функционирующий balanceManager как часть нашего Торгового Автомата.