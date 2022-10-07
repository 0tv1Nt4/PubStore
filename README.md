# PubStore
Usefull links, tools and more

---

# WEB

# FORENSIC
- [Autopsy](https://www.autopsy.com/)
- [Volatility](https://github.com/volatilityfoundation/volatility)

# STEGANO
- [Stegsolve](https://wiki.bi0s.in/steganography/stegsolve/)
- [Steghide](https://steghide.sourceforge.net/)
- [Audacity](https://www.audacityteam.org/)

# REVERSE
- [gdb](https://www.sourceware.org/gdb/) - консольный дебаггер под линь.
- [radare2](https://rada.re/n/) - консольный дебаггер под линь (более продвинутый, чем gdb).
- [Cutter](https://cutter.re/) - GUI для консольных дебаггеров (gdb, radare2)
- [Frida](https://frida.re/docs/examples/windows) - инжект кода в процесс. Мультиплатформенная (Linux, Windows, Android, MacOS)
- [Unicorn](https://www.unicorn-engine.org/) - CPU эмулятор (например, для эмуляции куска кода [шеллкода]). Фреймворк для python.
- [binwalk](https://www.kali.org/tools/binwalk/) - тулза поиска встроенных файлов, архивов и их извлечения.
- [strings](https://linux.die.net/man/1/strings) - для извлечения строк из файлов
- [grep](https://man7.org/linux/man-pages/man1/grep.1.html) и `egrep` (то же, что и `grep -E`) - для фильтрации вывода, а также поиска указанной строки в файле(-ах). Можно использовать регулярные выражения.
- [patchelf](https://manpages.ubuntu.com/manpages/bionic/man1/patchelf.1.html) - не патчит код. Может поменять loader ("ELF interpreter"), а также можно изменить RPATH (захардкоженные в бинарь пути, где происходит поиск импортируемых библиотек).
- [Ghidra](https://github.com/NationalSecurityAgency/ghidra) - бесплатный дизассемблер и декомпилятор (аналог IDA Pro). Мультиплатформенный (Windows, Linux, MACOs).
- [IDA Pro (+ Hex-Rays плагин для декомпиляции)](https://hex-rays.com/ida-pro/) - платный дизассемблер и декомпилятор. На просторах инета можно найти крякнутую версию с плагином.
- [IDR](https://github.com/crypto2011/IDR) - дизассемблер для exe-шников, написанных на Delphi.
- [VB Decompiler](https://www.vb-decompiler.org/products/rus.htm) - дизассемблер и декомпиллятор (для использования декомпилятора нужна верси VB Decompiler PRO [можно найти крякнутую]) для exe-шников, написанных на Visual Basic. Дизассемблирует как p-code, так и native code.
- [de4dot](https://github.com/de4dot/de4dot) - распаковщик и деобфускатор для .NET приложений.
- [DotPeek](https://www.jetbrains.com/decompiler/) - декомпилятор для .NET приложений. Достаточно тяжелый
- [ILSpy](https://github.com/icsharpcode/ILSpy) - более простой и легковесный (по сравнению с DotPeek) декомпилятор для .NET приложений. Обычно ILSpy хватает для анализа .NET бинарей.
- [dnSpy](https://github.com/dnSpy/dnSpy) - дебаггер для .NET приложений.
- [Kaitai](https://github.com/kaitai-io/kaitai_struct_formats) - парсер разных форматов файлов. Можно описывать свои форматы. [Онлайн версия](https://ide.kaitai.io) и [локальная версия](https://github.com/kaitai-io/kaitai_struct_visualizer)
- [D-810](https://eshard.com/posts/d810-deobfuscation-ida-pro) - IDA Pro плагин для деобфускации.
- [uncompyle6](https://pypi.org/project/uncompyle6/) - декомпилятор байт-кода питона (pyc - файлы). Декомплирует все версии ниже 3.9
- [decompile3](https://github.com/rocky/python-decompile3) - декомпилятор байт-кода питона версий 3.7-3.8
- [pycdc](https://github.com/zrax/pycdc) - может декомпилировать и дизаcсемлировать байт-код питона версии 3.10. Релизной версии нет, поэтому нужно скомпилировать.
- ....

> чуть позже сформирую примеры работы с этими тулзами

# PWN
- nc (netcat)
- [Генератор реверс шеллов](https://www.revshells.com/) - быстрая генерация скриптов, предназначенных для создания обратного подключения на атакуемом сервере.
- [pwntools](https://github.com/Gallopsled/pwntools) - удобный фреймворк (для python) для CTF и AD (написание эксплоитов (aka PoC-ов))
- [hexinject](https://hexinject.sourceforge.net/) - для создания кастомных сетевых пакетов, а также перехвата и инжекта. Также есть возможность работать с USB устройствами: создание, перехват и изменение передаваемых пакетов данных.
- ngrok
---
@hehe
