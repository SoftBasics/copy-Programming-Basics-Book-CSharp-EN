#### Преброяване на кравите

Проверката за крави можем да направи по следния начин - първо проверяваме дали **първата цифра** от генерираното число **съвпада с втората**, **третата** или **четвъртата цифра** на секретното число. Примерна имплементация:

![](/assets/chapter-9-2-images/03.Bulls-and-cows-10.png)

След това последователно проверяваме дали **втората цифра** от генерираното число **съвпада с първата**, **третата** или **четвъртата цифра** на секретното число, дали **третата цифра** от генерираното число съвпада с **първата**, **втората** или **четвъртата цифра** на секретното число и накрая проверяваме дали **четвъртата цифра** от генерираното число съвпада с **първата**, **втората** или **третата цифра** на секретното число.