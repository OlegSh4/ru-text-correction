RU-Text-Correction
Алгоритмы обнаружения и исправления ошибок в русскоязычных текстах иноязычных авторов

Курсовая работа посвящена разработке и сравнению алгоритмов автоматического исправления ошибок в русскоязычных текстах, написанных иноязычными пользователями. В проекте используется дообучение модели FRED-T5 на специализированном датасете, а также проводится сравнение с другими методами, такими как Speller и ByT5.

Цель проекта — повысить качество автоматического исправления орфографических, грамматических и стилистических ошибок, характерных для носителей других языков, пишущих на русском.

В рамках работы:
	•	Дообучена модель FRED-T5 на датасете ai-forever/spellcheck_benchmark.
	•	Реализовано сравнение с другими методами.
	•	Выполнена автоматическая оценка качества с помощью метрик CHRF++ и BERTScore.
	•	Проанализированы сильные и слабые стороны каждого подхода.

Результаты оценки показывают, что дообученная модель FRED-T5 превосходит по качеству как оригинальную, так и альтернативные модели.


