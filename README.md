# Testovoe
Задача из тестового - задача Question Answering, решение такой задачи на датасете SQUAD уже есть на hugging face, поэтому за основу был взят код оттуда https://huggingface.co/learn/nlp-course/chapter7/7?fw=pt
В обучении моей модели(есть на hugging face https://huggingface.co/YuryCHep/sbert_large_nlu_ru_ktr) использовалась предобученная модель Сбера sberbank-ai/sbert_large_nlu_ru, которая по сравнеию с другими предобученными моделями показывала лучший результат на датасете Контура
В файле prediction.json находятся предсказания на тестовом датасете, в Kontur_Final.ipynb исследование, его можно открыть тут, либо в гугл колабе https://colab.research.google.com/drive/11o78AE02TtjWUE5Mc2SqLDuQISI7Xorp?usp=sharing. (Если нужно воспроизвести код, то стоит учитывать, что создание предсказаний у меня заняло порядка 45 минут)
Для Fine-tunning использовался Trainer API
