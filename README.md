plainrussian
============

Plain Russian Language / Понятный (простой) русский язык.

* textmetric - примеры текстов и метрика расчета читаемости текстов.

textmetric/metrics.csv - перечень метрик 
======================

* filename - имя файла в папке textsbygrade
* name - название текста
* grade - год обучения необходимый для понимания текста, экспертная оценка
* index_fk_rus - измерение сложности текста в годах обучения по формуле Flesch-Kinkaid 
* fk_grade_diff - разница в измерении сложности по формуле Flesch-Kinkaid и предустановленной экспертной оценкой
* index_cl_rus - измерение сложности текста в годах обучения по формуле Coleman-Liau
* cl_grade_diff - разница в измерении сложности по формуле Coleman-Liau и предустановленной экспертной оценкой
* index_dc_rus - измерение сложности текста в годах обучения по формуле Dale-Chale
* dc_grade_diff - разница в измерении сложности по формуле Dale-Chale и предустановленной экспертной оценкой
* index_SMOG_rus - измерение сложности текста в годах обучения по формуле SMOG
* SMOG_grade_diff - разница в измерении сложности по формуле SMOG и предустановленной экспертной оценкой
* index_ari_rus - измерение сложности текста в годах обучения по формуле Automatic Readability Index
* ari_grade_diff - разница в измерении сложности по формуле Automatic Readability Index и предустановленной экспертной оценкой
* chars - число знаков в тексте
* spaces - число пробелов
* letters - число букв
* n_syllabes - общее число слогов 
* n_words - общее число слов
* n_complex_words - число сложных слов
* n_simple_words - число простых слов
* n_sentences - число предложений
* c_share - доля сложных слов в процентах
* avg_syl - среднее число слогов на слово
* avg_slen - среднее число слов на слово
* wsyllabes - словарь частоты слов по количеству слогов значений в формате { "число слогов" : "число слов"}
