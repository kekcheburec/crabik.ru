# crabik

![crabik](https://crabik.ru/_media/crabik-foto.png)

## Описание
Мозгом платы является микроконтроллер [nRF52810](https://www.nordicsemi.com/Products/Low-power-short-range-wireless/nRF52810) компании Nordic Semiconductor.
Внутри него ядро Arm Cortex-M4, работающее на частоте 64Mhz.

Для загрузки программы на микроконтроллер используется отдельная микросхема отладки совместимая с протоколом CMSIS-DAP v1.

Плата питается от USB-C или от напряжения поданого на вход контакта `VCC`.
Максимально допустимый ток от контакта `3.3v` - 400mA.

## Макет
Вид сверху

![crabik_front](https://crabik.ru/_media/crabik_front.png)

Вид снизу

![crabik_back](https://crabik.ru/_media/crabik_back.png)

## Файлы дизайна
- [Схема](https://crabik.ru/_assets/crabik-schematic-revB.pdf ':ignore :target=_blank')  
- [Интерактивный BOM](https://crabik.ru/ibom.html)
- [Файлы KiCad](https://github.com/CrabikBoards/hardware)

## Заказать
На данный момент можно [заказать производство печатной платы с монтажом у JLCPCB](https://github.com/CrabikBoards/hardware/blob/master/PRODUCTION.md), а недостающие компоненты допаять в ручную.
