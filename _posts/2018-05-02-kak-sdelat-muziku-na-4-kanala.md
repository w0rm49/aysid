---
layout: post
title:  "Как сделать музыку на 4 канала и больше"
date:   2018-05-02
---

Музыкантам - Как сделать музыку на 4 канала и больше.
МУЗЫКАНТАМ
──────────────────────────────────────────
(C) MastSoft

Приветствую  вас,  дорогие читатели! В
прошлом    номере   газеты   "Move"   была
опубликована  моя  маленькая статья о том,
как   сделать  эффект  эха  в  музыкальном
редакторе Pro-Tracker (или аналогичном). В
конце    предыдущей    статьи   я   обещал
рассказать  вам про то, как сделать музыку
на  4  канала  и  больше.  Давайте я сразу
обьясню  в чем тут дело. Итак, сопроцессор
AY-8910/12  имеет  3  независимых  друг от
друга  канала.  Три  -  и никак не больше.
Чтобы  сварганить  музон,  например  на  4
канала,  нужно  совмещать  в  одном канале
несколько    музыкальных    сопровождений,
например,  ударник и бас, бас и орнамент и
т.п.  Чтобы  совместить  бас и ударник или
ударник  и  орнамент на одном канале много
ума  и  умения  не требуется... Здесь же я
вас   научу   совмещать   бас,  ударник  и
орнамент    на   одном   канале!!!
Итак, приступим.

Для начала нам потребуется:
- 1 сэмпл для барабана (его номер будет 4)
- 2 сэмпла для тарелок (номера 5 И 6)
- 1 сэмпл для баса (номер 7)
- 1 сэмпл для орнамента (номер A)
- 2 орнамента (их структура и номера ниже)

Орнамент номер 3 - B+0
+3
+7E

Орнамент номер 4 - B+0
+4
+7E

Возьмем  паттерн на 16 кварков и расставим
барабаны и тарелки:

00 │ C_5 4F0F │
01 │ -------- │
02 │ -------- │
03 │ -------- │
04 │ C_4 5F0F │
05 │ -------- │
06 │ -------- │
07 │ -------- │
08 │ C_5 4F0F │
09 │ -------- │
10 │ -------- │
11 │ C_4 6F0F │
12 │ C_4 5000 │
13 │ -------- │
14 │ -------- │
15 │ -------- │

Теперь ко всему этому добавим бас:

00 │ C-5-4F0F │
01 │ F#4-7A00 │
02 │ -------- │
03 │ -------- │
04 │ C-4-5F0F │ 
05 │ F#4-7A00 │
06 │ -------- │
07 │ -------- │
08 │ C-5-4F0F │
09 │ D-4-7A00 │
10 │ -------- │
11 │ C-4-6F0F │
12 │ C-4-5000 │
13 │ D-4-7A00 │
14 │ -------- │
15 │ -------- │

Обратите  внимание,  что мы расставили бас
сразу  после  барабанов и тарелок, то есть
как  бы  соединили  два  сэмпла  в  один :
барабан и бас, и тарелку и бас.
Далее  наша  задача  втиснуть  в  этот
изврат  еще  и  орнамент, да так, чтобы он
еще и в ритм поквакивал - попробуем!

00 │ C-5-4F0F │
01 │ F#4-7A00 │
02 │ F#4-AF3D │
03 │ -------- │
04 │ C-4-5F0F │
05 │ F#4-7A00 │
06 │ F#4-AF3D │
07 │ F#4-0000 │
08 │ C-5-4F0F │
09 │ D-4-7A00 │
10 │ D-4-AF4D │
11 │ C-4-6F0F │
12 │ C-4-5000 │
13 │ D-4-7A00 │
14 │ D-4-AF4D │
15 │ D-4-0000 │

Вот   и   все!  Конечно,  барабаны  и  бас
довольно простые, да и орнамент не фонтан,
но я думаю, что все вместе звучит довольно
неплохо  (тем  более  на одном канале). На
оставшихся двух забомбите соло, желательно
с   крутым   эхом  (благо  есть  свободный
канал), и музон готов !!!

Дерзайте,  пишите  крутую музыку - я скоро
ухожу в войска, а из известных мне хороших
музыкантов  в Минске только Doc и McMaker.
Bye !!!