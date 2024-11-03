# Linux byedpi portable
Пренастроенное, переносное решение для обхода блокировок для линукса.

В комплекте скомпилированный [byedpi](https://github.com/hufrea/byedpi) под amd64.
Работает без рут-прав и на любом дистрибутиве* (поддержка musl не тестировалась)

## Инструкция по запуску

```bash
git clone https://github.com/ficache/linux-byedpi-general
cd linux-byedpi-general
./run_byedpi
```
При успешном запуске в консоль ничего не выведется. 

После запуска на вашем ПК откроется локальный 
**SOCKS v5** прокси сервер по адресу `127.0.0.1:1080`

## Какие сайты точно разблокирует?
Youtube, discord

## На каких провайдерах точно работает
-[x] Ростелеком

# Исходный код программы
- [byedpi](https://github.com/hufrea/byedpi)
