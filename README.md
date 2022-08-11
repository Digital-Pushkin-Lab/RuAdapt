# RuAdapt: A Parallel Russian-Simple Russian Dataset  

**На русском ниже/In Russian below**

RuAdapt is a parallel dataset in which target texts are simplified versions of the source texts. It is suitable for automatic text simplification as well as for studying how human experts simplify texts.

## Contents

RuAdapt consists of texts adapted for learners of Russian as a Foreign Language and their original versions. Most of the materials are from adapted Russian literature books kindly provided by the Zlatoust publishing house (see Adapted_literature). Some of the texts are encyclopedic entries written and adapted by researchers from the Pushkin State Russian Language Institute (see Encyclopedic), and a small part is composed of Russian fairytales adapted by recearchers from the Moscow State University (see Fairytales).  

## Alignments  

RuAdapt has paragraph and sentence level alignments. The original and adapted texts were aligned automatically. We used two aligners: Bleualign (https://github.com/rsennrich/Bleualign) and CATS (https://github.com/neosyon/SimpTextAlign). Both versions can be found in the repository. For CATS, we also preserved the cousine similarity scores for each paragraph pair.

## CEFR levels

There is a level specified for each paragraph or sentence pair. This is the level of Russian language acquisition for which the target paragraph has been adapted. For some pairs, only an approximate level (like B1-B2) is specified. The exact proportions of the adapted texts for each level are given in the descriptions of the subcorpora.  

### Publications

Dmitrieva, A., Laposhina, A., & Lebedeva, M. (2021, June). A quantitative study of simplification strategies in adapted texts for L2 learners of Russian. In Proceedings of the International Conference "Dialogue" (pp. 191-203). URL: http://www.dialog-21.ru/media/5504/dmitrievaapluslaposhinaapluslebedevam099.pdf  

Dmitrieva, A., & Tiedemann, J. (2021, April). Creating an Aligned Russian Text Simplification Dataset from Language Learner Data. In Proceedings of the 8th Workshop on Balto-Slavic Natural Language Processing (pp. 73-79). URL: https://www.aclweb.org/anthology/2021.bsnlp-1.8/  

---------

## Dataset statistics / Статистика датасета

### Paragraph-aligned version / Пары параграфов  

| Subcorpus / Подкорпус | Texts / Тексты | Original tokens / Токены в исходных текстах | Adapted tokens / Токены в адаптированных текстах | Paragraphs / Параграфы |
|-----------------------|----------------|---------------------------------------------|--------------------------------------------------|----------------|
| Adapted literature    |             93 |                                      620563 |                                           287358 |           7614 |
| Encyclopedic texts    |            355 |                                      207252 |                                           144378 |           3517 |
| Fairytales            |              9 |                                        7093 |                                             4652 |            134 |

### Sentence-aligned version / Пары предложений 

| Subcorpus / Подкорпус | Texts / Тексты | Original tokens / Токены в исходных текстах | Adapted tokens / Токены в адаптированных текстах | Sentences / Предложения |
|-----------------------|----------------|---------------------------------------------|--------------------------------------------------|----------------|
| Adapted literature    |             93 |                                      376432 |                                           285190 |          24232 |
| Encyclopedic texts    |            355 |                                      161954 |                                           144250 |          10271 |
| Fairytales            |              9 |                                        5775 |                                             4642 |            416 |

More detailed statistics can be found on the subcorpora pages / С более подробной статистикой можно ознакомиться на страницах подкорпусов.

---------

# RuAdapt: параллельный датасет упрощенного русского языка

RuAdapt — это параллельный датасет, в котором результирующие (target) тексты являются упрощенными версиями исходных (source) текстов. Он подходит для автоматического упрощения текста, а также для изучения того, как специалисты упрощают тексты.

## Содержание

RuAdapt состоит из текстов, адаптированных для изучающих русский язык как иностранный, и их оригинальных версий. Большинство материалов взяты из адаптированной литературы, любезно предоставленной издательством "Златоуст" (см. Adapted_literature). Некоторые тексты представляют собой энциклопедические статьи, написанные и адаптированные исследователями из ГосИРЯ имени Пушкина (см. Encyclopedic), а небольшая часть состоит из русских сказок, адаптированных исследователями из Московского государственного университета (см. Fairytales).

## Выравнивания

RuAdapt выравнен на уровне параграфов и предложений. Оригинальные и адаптированные тексты были выравнены автоматически. Мы использовали два элайнера: Bleualign (https://github.com/rsennrich/Bleualign) и CATS (https://github.com/neosyon/SimpTextAlign). Обе версии можно найти в репозитории. Для CATS мы также сохранили значения косинусного подобия для каждой пары абзацев.  

## Уровни РКИ

Для каждой пары параграфов или предложений указан уровень. Это уровень владения русским как иностранным, для которого был адаптирован результирующий абзац. Для некоторых пар указан только приблизительный уровень (например, B1-B2). Точные пропорции адаптированных текстов для каждого уровня указаны в описаниях к подкорпусам.  

### Публикации

Dmitrieva, A., Laposhina, A., & Lebedeva, M. (2021, June). A quantitative study of simplification strategies in adapted texts for L2 learners of Russian. In Proceedings of the International Conference "Dialogue" (pp. 191-203). URL: http://www.dialog-21.ru/media/5504/dmitrievaapluslaposhinaapluslebedevam099.pdf  

Dmitrieva, A., & Tiedemann, J. (2021, April). Creating an Aligned Russian Text Simplification Dataset from Language Learner Data. In Proceedings of the 8th Workshop on Balto-Slavic Natural Language Processing (pp. 73-79). URL: https://www.aclweb.org/anthology/2021.bsnlp-1.8/  

