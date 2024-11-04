# Drozdov Phd Dissertation

Диссертация на соискание ученой степени кандидата физико-математических наук по специальности 1.1.1 Вещественный, комплексный и функциональный анализ

Соискатель:
Дроздов Дмитрий Алексеевич


Тема диссертации:
Анализ на самоподобных множествах с конечным пересечением

Размещение диссертации: 
[math.nsc.ru/dis-council/dissert](https://math.nsc.ru/dis-council/dissert)

Дата размещения: 19 сентября 2024 г.


## Структура

* &#128193; `common`: файлы для преамбулы, общие для диссертации и квалификационной работы
	* &#128196; `disstyles.tex`: стилевые опции
	* &#128196; `newnames.tex`: новые и переопределённые команды
	* &#128196; `packages.tex`: подлючение и настройка пакетов
* &#128193; `dissertation`: составные компоненты кандидатсткой диссертации
* &#128193; `documents`: документы для защиты
* &#128193; `images`: файлы с изображениями, общие для диссертации, презентации и квалификационной работы
* &#128193; `qualification-work`: составные компоненты квалификационной работы
* &#128196; `.gitignore`: собран сервисом [gitignore.io](https://www.toptal.com/developers/gitignore/) и дополнен в GitHub Desktop
* &#128196; `dissbib.bib`: файл с библиографией. не задействован, но обновляется
* &#128196; `dissertation.tex`: собирающий файл кандидатской диссертации
* &#128196; `presentation.tex`: старая версия презентации, требуется переработка
* &#128196; `qualification-work.tex`: собирающий файл квалификационной работы
* &#128196; `QW_presentation.tex`: презентация для защиты квалификационной работы
* &#128196; `referat`: реферат для защиты квалификационной работы
* &#128196; `synopsis-final.tex`: автореферат с подписью Подвигина.


## Замечания

* На стр. 41 в формуле (2.14) при раскрытии модуля суммы надо бы поставить знак `≤` вместо `<`. Если должен стоять знак `≤`, то необходимы пояснения, почему строго неравенство.
* Лемма 2.22 на стр. 42: для читателя будет удобнее, если определить число `λ` в самой формулировке леммы, а не в доказательстве.
* Во второй главе наблюдаются ссылки на формулы без скобок:
	* на формулы (2.9), (2.15), (2.16), (2.18) на стр. 44;
	* на условие (2.1) на стр. 28 и 30.
* Предложение 3.5 имеет некорректное доказательство
* Первое утверждение Главы 4 начинается со следствия 4.2, но не указано следствие из какого утверждения.
* В Главе 4 втречаются некорректные ссылки на некоторые утверждения:
	* на стр. 60 в доказательстве Следствия 4.4 дважды встречается ссылка на Следствие 3.11, а должно быть Следствие 4.3;
	* на стр. 65 ссылка на предложение 4.6, а должно быть предложение 4.8;
	* на стр. 71 и 73 ссылки на Теорему 4.11, а должны быть на Лемму 4.11.
* Предложение 4.6 из автореферата и Главы 1 превратилось в четвёртой главе в Теорему 4.6.
	
