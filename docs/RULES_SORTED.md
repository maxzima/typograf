## Правила типографа по порядку выполнения

| № | [Имя](./RULES.md) | Название | Индекс | Очередь | Вкл. |
|--:|-------------------|----------|-------:|:----:--:|:----:|
| 1. | [common/sym/copy](../src/rules/common/sym/copy.js) | (c) → ©, (tm) → ©, (r) → ™ | 10 |  | ✓ |
| 2. | [common/punctuation/hellip](../src/rules/common/punctuation/hellip.js) | Три точки на троеточие | 20 |  | ✓ |
| 3. | [ru/dash/to](../src/rules/ru/dash/to.js) | Дефис перед то, либо, нибудь, ка, де, кась | 30 |  | ✓ |
| 4. | [ru/dash/izza](../src/rules/ru/dash/izza.js) | Дефис между из-за | 33 |  | ✓ |
| 5. | [ru/dash/izpod](../src/rules/ru/dash/izpod.js) | Дефис между из-под | 35 |  | ✓ |
| 6. | [ru/dash/koe](../src/rules/ru/dash/koe.js) | Дефис после кое и кой | 38 |  | ✓ |
| 7. | [ru/dash/taki](../src/rules/ru/dash/taki.js) | Дефис между верно-таки и т.д. | 39 |  | ✓ |
| 8. | [common/html/url](../src/rules/common/html/url.js) | Расстановка ссылок | 200 |  | ✓ |
| 9. | [common/space/delLeadingBlanks](../src/rules/common/space/delLeadingBlanks.js) | Удаление пробелов в начале строки | 504 |  |  |
| 10. | [common/space/delTrailingBlanks](../src/rules/common/space/delTrailingBlanks.js) | Удаление пробелов в конце строки | 505 |  | ✓ |
| 11. | [common/space/replaceTab](../src/rules/common/space/replaceTab.js) | Замена таба на 4 пробела | 510 |  | ✓ |
| 12. | [common/space/trimLeft](../src/rules/common/space/trimLeft.js) | Удаление пробелов и переносов строк в начале текста | 530 |  | ✓ |
| 13. | [common/space/trimRight](../src/rules/common/space/trimRight.js) | Удаление пробелов и переносов строк в конце текста | 535 |  | ✓ |
| 14. | [common/space/delRepeatSpace](../src/rules/common/space/delRepeatSpace.js) | Удаление повторяющихся пробелов между символами | 540 |  | ✓ |
| 15. | [common/space/delRepeatN](../src/rules/common/space/delRepeatN.js) | Удаление повторяющихся переносов строки (не более двух) | 545 |  | ✓ |
| 16. | [common/space/delBeforePunctuation](../src/rules/common/space/delBeforePunctuation.js) | Удаление пробелов перед знаками пунктуации | 550 |  | ✓ |
| 17. | [common/space/afterPunctuation](../src/rules/common/space/afterPunctuation.js) | Пробел после знаков пунктуации | 560 |  | ✓ |
| 18. | [ru/nbsp/beforeParticle](../src/rules/ru/nbsp/beforeParticle.js) | Неразрывный пробел перед ли, ль, же, бы, б | 570 |  | ✓ |
| 19. | [common/punctuation/delDoublePunctuation](../src/rules/common/punctuation/delDoublePunctuation.js) | Удаление двойной пунктуации | 580 |  | ✓ |
| 20. | [common/nbsp/afterShortWord](../src/rules/common/nbsp/afterShortWord.js) | Нераз. пробел после короткого слова | 590 |  | ✓ |
| 21. | [ru/dash/weekday](../src/rules/ru/dash/weekday.js) | Тире между днями недели | 600 |  | ✓ |
| 22. | [common/space/delBeforePercent](../src/rules/common/space/delBeforePercent.js) | Удаление пробела перед %, ‰ и ‱ | 600 |  | ✓ |
| 23. | [common/nbsp/afterPara](../src/rules/common/nbsp/afterPara.js) | Нераз. пробел после § | 610 |  | ✓ |
| 24. | [ru/dash/month](../src/rules/ru/dash/month.js) | Тире между месяцами | 610 |  | ✓ |
| 25. | [ru/nbsp/page](../src/rules/ru/nbsp/page.js) | Неразрывный пробел перед стр., гл., рис., илл. | 610 |  | ✓ |
| 26. | [ru/nbsp/afterNumberSign](../src/rules/ru/nbsp/afterNumberSign.js) | Неразрывный пробел после № | 610 |  | ✓ |
| 27. | [ru/nbsp/afterNumber](../src/rules/ru/nbsp/afterNumber.js) | Нераз. пробел между числом и словом | 615 |  | ✓ |
| 28. | [ru/nbsp/beforeShortLastWord](../src/rules/ru/nbsp/beforeShortLastWord.js) | Неразрывный пробел перед последним коротким словом в предложении | 620 |  | ✓ |
| 29. | [ru/dash/main](../src/rules/ru/dash/main.js) | Дефис на тире | 620 |  | ✓ |
| 30. | [common/nbsp/beforeShortLastWord](../src/rules/common/nbsp/beforeShortLastWord.js) | Нераз. пробел перед последним коротким словом в предложении | 620 |  | ✓ |
| 31. | [common/html/pbr](../src/rules/common/html/pbr.js) | Расстановка тегов p и br | 700 |  |  |
| 32. | [ru/punctuation/quot](../src/rules/ru/punctuation/quot.js) | Расстановка кавычек | 700 |  | ✓ |
| 33. | [common/html/nbr](../src/rules/common/html/nbr.js) | Замена перевода строки на тег br | 710 |  |  |
| 34. | [ru/optalign/quot](../src/rules/ru/optalign/quot.js) | Висячая пунктуация для открывающей кавычки | 1000 |  |  |
| 35. | [ru/optalign/bracket](../src/rules/ru/optalign/bracket.js) | Висячая пунктуация для открывающей скобки | 1001 |  |  |
| 36. | [ru/optalign/comma](../src/rules/ru/optalign/comma.js) | Висячая пунктуация для запятой | 1002 |  |  |
| 37. | [common/number/plusMinus](../src/rules/common/number/plusMinus.js) | +- → ± | 1010 |  | ✓ |
| 38. | [common/sym/cf](../src/rules/common/sym/cf.js) | Добавление ° к C и F | 1020 |  | ✓ |
| 39. | [ru/nbsp/m](../src/rules/ru/nbsp/m.js) | m2 → м², m3 → м³ и неразрывный пробел | 1030 |  | ✓ |
| 40. | [common/number/times](../src/rules/common/number/times.js) | x → × (10 x 5 → 10×5) | 1050 |  | ✓ |
| 41. | [ru/nbsp/xxxx](../src/rules/ru/nbsp/xxxx.js) | Неразрывный пробел после XXXX г. (2012 г.) | 1060 |  | ✓ |
| 42. | [ru/nbsp/yy](../src/rules/ru/nbsp/yy.js) | г.г. → гг. и неразрывный пробел | 1080 |  | ✓ |
| 43. | [ru/nbsp/cc](../src/rules/ru/nbsp/cc.js) | Удаление пробелов и лишних точек в вв. | 1090 |  | ✓ |
| 44. | [ru/nbsp/ooo](../src/rules/ru/nbsp/ooo.js) | Неразрывный пробел после OOO, ОАО, ЗАО, НИИ и ПБОЮЛ | 1100 |  | ✓ |
| 45. | [ru/nbsp/dayMonth](../src/rules/ru/nbsp/dayMonth.js) | Неразрывный пробел между числом и месяцем | 1105 |  | ✓ |
| 46. | [ru/nbsp/but](../src/rules/ru/nbsp/but.js) | Расстановка запятых и неразрывного пробела перед а и но | 1110 |  | ✓ |
| 47. | [common/number/fraction](../src/rules/common/number/fraction.js) | 1/2 → ½, 1/4 → ¼, 3/3 → ¾ | 1120 |  | ✓ |
| 48. | [common/sym/arrow](../src/rules/common/sym/arrow.js) | -> → →, <- → ← | 1130 |  | ✓ |
| 49. | [ru/money/euro](../src/rules/ru/money/euro.js) | €100 → 100 € | 1140 |  | ✓ |
| 50. | [ru/money/dollar](../src/rules/ru/money/dollar.js) | $100 → 100 $ | 1140 |  | ✓ |
| 51. | [common/punctuation/exclamationQuestion](../src/rules/common/punctuation/exclamationQuestion.js) | !? → ?! | 1140 |  | ✓ |
| 52. | [ru/money/ruble](../src/rules/ru/money/ruble.js) | 1 руб. → 1 ₽ | 1145 |  |  |
| 53. | [common/punctuation/exclamation](../src/rules/common/punctuation/exclamation.js) | !! → ! | 1150 |  | ✓ |
| 54. | [common/nbsp/dpi](../src/rules/common/nbsp/dpi.js) | Нераз. пробел перед lpi, dpi | 1150 |  | ✓ |
| 55. | [common/other/repeatWord](../src/rules/common/other/repeatWord.js) | Удаление повтора слова | 1200 |  |  |
| 56. | [ru/date/main](../src/rules/ru/date/main.js) | Преобразование дат YYYY-MM-DD к виду DD.MM.YYYY | 1300 |  | ✓ |
| 57. | [ru/number/ordinals](../src/rules/ru/number/ordinals.js) | N-ый, -ой, -ая, -ое, -ые, -ым, -ом, -ых → N-й, -я, -е, -м, -х (25-й) | 1300 |  | ✓ |
| 58. | [ru/date/weekday](../src/rules/ru/date/weekday.js) | 2 Мая, Понедельник → 2 мая, понедельник | 1310 |  | ✓ |
| 59. | [common/nbsp/nowrap](../src/rules/common/nbsp/nowrap.js) | Заменять нераз. пробел на обычный пробел в тегах nowrap и nobr | 1400 |  | ✓ |
| 60. | [common/html/stripTags](../src/rules/common/html/stripTags.js) | Удаление HTML-тегов | 5 | end |  |
| 61. | [common/html/escape](../src/rules/common/html/escape.js) | Экранирование HTML | 10 | end |  |