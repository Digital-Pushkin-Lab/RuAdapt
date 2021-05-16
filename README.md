# RuAdapt: A Parallel Russian-Simple Russian Dataset  

**На русском ниже/In Russian below**

RuAdapt is a parallel dataset aligned on the paragraph level, in which target paragraphs are simplified versions of the source paragraphs. It is suitable for automatic text simplification as well as for studying how human experts simplify texts.

## Contents

The simplified texts in RuAdapt are Russian literature texts adapted for learners of Russian as a foreign language. The adapted books were kindly provided by the Zlatoust publishing house (https://www.zlat.spb.ru/). The source texts were crawled from open sources.  

**NB!** Unfortunately, not all books that were provided by Zlatoust were included in the public version of RuAdapt due to some of the original texts not being in public domain yet. However, we managed to include the majority of the collection in this public dataset.  

List of novels included in the dataset (in Russian): https://bit.ly/3hwGOJE

## Alignments  

The original and adapted texts were aligned automatically. We used two aligners: Bleualign (https://github.com/rsennrich/Bleualign) and CATS (https://github.com/neosyon/SimpTextAlign). Both versions can be found in the repository. For CATS, we also preserved the cousine similarity scores for each paragraph pair.

## RaaFL levels

There is a level specified for each paragraph pair. This is the level of Russian language acquisition for which the target paragraph has been adapted. For some pairs, only an approximate level (like B1-B2) is specified. This happens because in the collections of novels the level is only specified for the whole collection, not for each separate text. Most of the texts on RuAdapt are for level B1.  

### Publications

Dmitrieva, A., & Tiedemann, J. (2021, April). Creating an Aligned Russian Text Simplification Dataset from Language Learner Data. In Proceedings of the 8th Workshop on Balto-Slavic Natural Language Processing (pp. 73-79). URL: https://www.aclweb.org/anthology/2021.bsnlp-1.8/  

---------

# RuAdapt: параллельный датасет упрощенного русского языка

RuAdapt — это параллельный датасет, выровненный на уровне абзацев, в котором результирующие (target) абзацы являются упрощенными версиями исходных (source) абзацев. Он подходит для автоматического упрощения текста, а также для изучения того, как специалисты упрощают тексты.

## Содержание

Упрощенные тексты в RuAdapt - это произведения русской литературы, адаптированные для изучающих русский язык как иностранный. Адаптированные книги были любезно предоставлены издательством "Златоуст" (https://www.zlat.spb.ru/). Исходные тексты были извлечены из открытых источников.

**NB!** К сожалению, не все книги, предоставленные издательством, были включены в общедоступную версию RuAdapt из-за того, что некоторые оригинальные тексты еще не перешли в общественное достояние. Тем не менее, нам удалось выложить в открытый доступ большую часть коллекции.

Список текстов, вошедших в датасет: https://bit.ly/3hwGOJE

## Выравнивания

Оригинальные и адаптированные тексты были выровнены автоматически. Мы использовали два элайнера: Bleualign (https://github.com/rsennrich/Bleualign) и CATS (https://github.com/neosyon/SimpTextAlign). Обе версии можно найти в репозитории. Для CATS мы также сохранили значения косинусного подобия для каждой пары абзацев.

## Уровни РКИ

Для каждой пары абзацев указан уровень. Это уровень владения русским как иностранным, для которого был адаптирован результирующий абзац. Для некоторых пар указан только приблизительный уровень (например, B1-B2). Это сделано потому, что в сборниках произведений уровень указан только для всего сборника, а не для каждого отдельного текста. Большинство текстов в RuAdapt предназначены для уровня B1.

### Публикации

Dmitrieva, A., & Tiedemann, J. (2021, April). Creating an Aligned Russian Text Simplification Dataset from Language Learner Data. In Proceedings of the 8th Workshop on Balto-Slavic Natural Language Processing (pp. 73-79). URL: https://www.aclweb.org/anthology/2021.bsnlp-1.8/  

