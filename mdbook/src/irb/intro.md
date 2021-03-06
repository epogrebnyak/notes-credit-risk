# IRB подход: введение

## Тезисы

- На ранней стадии регулирования (Базель I) - различным типам активов присваивались веса от 0 до 150% и
  требования по минимальному капиталу рассчитывались как доля от активов взвешенных этими весами. Если
  установить повышенный вес какому-либо типу активов, 

- Простое правило - "капитал должен быть 8% от RWA" недооценивает потребность банков в капитале.
  Требования по капиталу слишком низкие, банки слишком расширяют активы, принимают на себя избыточные 
  риски того, что эти активы обесценятся.

- Для разбора: как банки могут увелчить достаточность капитала? Действия на стороне активов 
  (выдачи, продажа части портфеля, операции с ликвидностью) vs действия на стороне пассивов 
  (докапитализация, дивиденды).

- Вспоминаем как считается RWA, для корпоративных кредитов вес 100%, для ликвидности - 0%.

- Безотносительно к регулированию банки занимаются сбром статистики по дефолтам (PD) и величине потерь 
  при дефолтах (LGD) - для ценообразования на кредиты и для того, чтобы обосновать свои действия по 
  расширению или другим действиям с кредитным портфелем перед акционерами. 

- Если фактического капитала больше, чем требуемого (экономического) капитала - банк защищен перед значительной 
  долей возможных потерь (на заданном уровне, например, 99.9%). 

- Исходя из той же информации банка о PD и LGD можно построить модель, которая будет рассчитывать требуемую величину 
  регуляторного капитала (K). Базельский комитет принял опредленный тип модели кредитного риска, в рамках которого 
  рассчитывается такой переход от PD и LGD к K. Объем активов взвешенных по величине риска считается через K.

- Модель IRB несовершенна, в ней есть различные "довески", увеличивающие капитал (по типам активов, по видам финансовых   
  инстутитов). 

- Критика IRB подхода в том, что регулирование сильно усложнилось, а его эффективность - под вопросом.
  Также более сложное регулирование на руку более крупным банкам. Для обсуждения - почему, из-за каких механизмов.
  Также рынки для консультантов.

- Зарубежные банки активно используют IRB-модели, так как это позволяет им снизить требовани по величине
  капитала. Мы можем посмотреть распространение IRB-подхода в публичных отчетах банков по Basel Pillar 3
  (третий уровень базельских требований, связанных с раскрытием информации).

- На практике - IRB для целей регулирования и для внутреннего использования менеджментом - не совсем одно и то же.
  Результат регуляторных моделей - их валидация у регулятора, и мотив снижения требований к капиталу (хотя обычно банки 
  не балансируют на грани этих требований). Результат внутренних работ, близких к сфере IRB, связаны с целью получения прибыли
  и изменения. 


Дополнителельные замечания:

- Отлично работает в розничной кредтовании. Вопрос - почему?
- Нужно 5 лет сбора данных, причем приходящихся на разные фазы экономического цикла (будем смотреть в лекции про кредитные циклы).  


## Термины

- RWA
- PD
- LGD
- EAD
- IRB/ВПОДК
- EL
- UL
- Tier 1, Tier 2 капитал (добавить определения, что туда входит)

## Примеры

- простой расчет RWA
- [Старетегия управления рисками и капиталом Группы ПАО Сбербанк](https://www.sberbank.com/common/img/uploaded/files/pdf/normative_docs/group_risk-and-capital-strategy_rus.pdf) (доступные ресурсы > экономический капитал)
- введение в отчет об экономическом капитале (пример - Deutsche Bank)
- новость о внетрении IRB Райфа (высвободили капитал, хотя им и некритично)
- отчеты об Basel Pillar 3 для крупных банков (G-SIB)

## Сложности восприятия

1. часть показателей мы видим из бухучета (EAD) или можем оттуда получить (RWA), а часть - очень аналитические (экономический 
  капитал), "пощупать руками" их сложно
2. часть концепций относится к регулированию (регуляторный капитал), часть к управлению со стороны акционеров (экономический 
  капитал), а часть терминов к тому и к тому (достаточность капитала)
3. связь капитала с unexpected loss неинтуитивна и не прослеживаема на уровне бухучета, покрытие expected loss резервами 
  также можно считать желаемым совпадением, но не гарантией (резервы начисляются исходя из оценок ожидаемых потерь,
  но их уровень для одной и той же ситуации может сильно отличаться в зависимости от внутренней политики банка).

## Вопросы

- Как здесь рассказать про "аппетит к риску"
- Есть ли какие-то наглядные примеры расчета экономического капитала, организации работ по внутренним рейтингам


## Почитать

- [How much capital should banks have?](https:/voxeu.org/article/how-much-capital-should-banks-have)

- [Comparability of Basel risk weights in the EU banking sector is questionable ](https://voxeu.org/article/bank-risk-weights-under-basel-are-not-comparable)


## Посмотреть

- [Логика расчета экономического капитала](https://ru.coursera.org/lecture/osnovy-risk-menedzhmenta-v-banke/komponient-2-loghika-raschieta-ekonomichieskogho-kapitala-SRc2H)