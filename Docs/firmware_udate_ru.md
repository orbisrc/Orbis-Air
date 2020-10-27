# Firmware update
- Скачай и установи утилиту [DfuSeDemo](https://www.st.com/en/development-tools/stsw-stm32080.html) 
- На плате MCU замкни контаты BOOT и 3.3V. 
- Плату подключи к компьютеру. Перемычку между BOOT и 3.3V можно убрать
- В диспетчере устрйоств появится STM32 download inteface. Windows автоматически установит драйвера. 
- Запусти DfuSeDemo

![DfuSeDemo](/image/firmware_update/dfuse_main_screen_w_marks.png)
1. Выбери устройство
2. Выбери "Internal flash"
3. Выбери прошивку, которую надо загрузить в устройство.
4. Отметь "Verify after download"
5. Нажми "Upgrade"

- Когда закончится процесс обновления по, выключи и включи устройство