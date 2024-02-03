# Beautiful-visual-effects-for-addressable-RGB-LED-strips


Коли з'явилися світлодіодні стрічки на драйверах WS28xx, колега попросив зробити ефект "блискавки" (було одне така відео з китайського джерела) для одного роесторану. Через деякий час мені захотілося написати кілька своїх ефектів для новорічної ялинки. Виникла ідея написати "дощик" та "сніг".
Був використаний 8-бітний МК STM8S103 і плата 
STM8_dev_kit . Схема показана на рис. 1 . Програми були написані спочатку в оглядовому варіанті на С, потім переведені "вручну" на асемблер STVD. Пізніше в схему додані змінні резистори для регулювання загальної яскравості та часових затримок (1. -швидкість переміщення об'єктів, 2.-час повторювання зображення). Надалі, можливо, додасться IRD пульт+блютуз. А головне - плануються нові красиві ефекти, котрих нема у виробників стрічок.
-------------------------------------------

Когда появились светодиодные ленточки на WS28xx, коллега попросил сделать эффект молнии (было одно соответствующее видео с китайского источника) для одного ресторана. Через некоторое время мне захотелось написать парочку своих эффектов
для новогодней ёлки. Возникла идея написать 'дождик' и 'снег'. 
Использован 8-битный МК STM8S103 и плата STM8_dev_kit . Схема представлена на рис.1 . Программы  писались вначале в обзорном варианте на С, затем переведены вручную на ассемблер STVD. Позже в схему добавились переменные резисторы для регулировки яркости и временных задержек (1.-скорость перемещения объектов, 2.- время повтора картинки). В дальнейшем, воможно, добавится IRD пульт+блютуз. Ну а главное - планируются новые красивые эффекты, которых нет у производителей ленточек.

-------------------------------------------
When LED strips on the WS28xx appeared, my colleague asked me to make a lightning effect (there was one corresponding video from a Chinese source) for one restaurant. After a while I wanted to write a couple of my own effects for the New Year tree. The idea arose to write 'rain' and 'snow'.

An 8-bit STM8S103 MCU and an STM8_dev_kit board were used. The diagram is presented in Fig. 1. The programs were first written in an overview version in C, then manually translated into STVD assembler. Later, variable resistors were added to the circuit to adjust brightness and time delays (1. - speed of object movement, 2. - picture repeat time). In the future, it is possible that an IRD remote control + bluetooth will be added. Well, most importantly, new beautiful effects are planned that strip manufacturers do not have.

Video:
https://drive.google.com/file/d/1SusUpxp6q4iR9_zBNOfhVI5OVD2T2UhP/view?usp=drive_link
https://drive.google.com/file/d/1Sl_AnIjD4ZojBQMkMsow1h1KfacIIdEX/view?usp=drive_link
