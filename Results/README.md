# Описание проекта

Выполнение задания лабораторной работы Lab SCR1 sim

## Вариант задания

|Параметр | Значение по варианту
|----— | —---------
|Вид исключения | Instruction address misaligned
|Тест | isa/rv32mi/ma_fetch.S
|Reset Vector | 0хA000
|Trap Vector | 0х8C0
|При обработке | Вывод строки "misalign"

## Результаты работы

* ./results/test_results.txt - результат симуляции
* ./results/ma_addr.dump - дамп теста
* ./results/trace_mprf_diff_.log - трейслог MPRF
* ./results/trace_csr_.log - трейслог CSR
