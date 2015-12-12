PETOOH – a fundamentally new programming language
==================================================

Basics
------

<table>
    <tr>
        <td>Kudah</td>
        <td>Передвигает указатель на другую ячейку памяти (инкремент)</td>
    </tr>
    <tr>
        <td>kudah</td>
        <td>Передвигает указатель на другую ячейку памяти (декиремнт)</td>
    </tr>
    <tr>
        <td>Ko</td>
        <td>Инкрементирует байт, на который установлен указатель</td>
    </tr>
    <tr>
        <td>kO</td>
        <td>Декрементирует байт, на который установлен указатель</td>
    </tr>
    <tr>
        <td>Kukarek</td>
        <td>Выводит на экран байт, на который установлен указатель, в виде ASCII символа</td>
    </tr>
    <tr>
        <td>Kud</td>
        <td>Выполняет следующую команду до тех пор, пока указатель не начнёт смотреть на ноль (своеобразный цикл)</td>
    </tr>
    <tr>
        <td>kud</td>
        <td>Конец своеобразного цикла</td>
    </tr>
</table>

Code sample
-----------

    KoKoKoKoKoKoKoKoKoKo Kud-Kudah
    KoKoKoKoKoKoKoKo kudah kO kud-Kudah Kukarek kudah
    KoKoKo Kud-Kudah
    kOkOkOkO kudah kO kud-Kudah Ko Kukarek kudah
    KoKoKoKo Kud-Kudah KoKoKoKo kudah kO kud-Kudah kO Kukarek
    kOkOkOkOkO Kukarek Kukarek kOkOkOkOkOkOkO
    Kukarek

[Try now!](http://ky6uk.github.io/PETOOH/)
