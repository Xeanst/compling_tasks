Репозиторий с материалами для курса "Методы машинного обучения для решения задач компьютерной лингвистики"

Данный курс призван сформировать практические навыки применения машинного обучения в задачах обработки текстов.

Он состоит из двух модулей, в каждом из которых будет подробна рассмотрена определенная задача компьютерной лингвистики: семантический модуль посвящен автоматическому распознаванию эмоций в тексте, синтаксический –автоматической оценке приемлемости предложений. Мы проанализируем, как данные задачи решаются в существующих исследованиях, разберем предложенные в статьях наборы данных и методы.

<!DOCTYPE html>
<html>
<table>
  <tr>
    <th>Тема</th>
    <th>Содержание</th>
    <th>Видеозапись</th>
    <th>Colab-блокнот</th>
  </tr>
  <tr>
    <td rowspan="2"><a href="https://github.com/Xeanst/NN_in_compling/tree/main/01_machine_learning">1. Классическое машинное обучение</a></td>
    <td rowspan="2"><ul>
  <li>Обучение с учителем и без учителя</li>
  <li>Библиотеки для анализа данных: numpy, pandas</li>
  <li>Методы векторизации: мешок слов, TF-IDF</li>
  <li>Методы машинного обучения: наивный байесовский классификатор, логистическая регрессия</li>
  <li>Оценка качества классификации</li>
</ul>  </td>
    <td><a href="https://teach-in.ru/lecture/2023-11-08-Studenikina">Лекция 1</a></td>
    <td><a href="https://github.com/Xeanst/NN_in_compling/blob/main/01_machine_learning/1a_machine_learning_with_gaps.ipynb">1a_with_gaps</a><br/><a href="https://github.com/Xeanst/NN_in_compling/blob/main/01_machine_learning/1a_machine_learning_no_gaps.ipynb">1a_no_gaps</a></td>
  </tr>
  <tr>
    <td><a href="https://teach-in.ru/lecture/2023-11-15-Studenikina">Лекция 2</a></td>
    <td><a href="https://github.com/Xeanst/NN_in_compling/blob/main/01_machine_learning/1b_machine_learning_with_gaps.ipynb">1b_with_gaps</a><br/><a href="https://github.com/Xeanst/NN_in_compling/blob/main/01_machine_learning/1b_machine_learning_no_gaps.ipynb">1b_no_gaps</a></td>
  </tr>
   <tr>
     <td><a href="https://github.com/Xeanst/NN_in_compling/tree/main/02_intro_to_nn">2. Введение в нейросетевые алгоритмы</a></td>
     <td><ul>
  <li>Что такое нейронная сеть</li>
  <li>Функция потерь</li>
  <li>Градиентный спуск</li>
  <li>Функция активации</li>
</ul>  </td>
    <td><a href="https://teach-in.ru/lecture/2023-11-22-Studenikina">Лекция 3</a></td>
    <td><a href="https://github.com/Xeanst/NN_in_compling/blob/main/02_intro_to_nn/2_intro_to_neural_networks_with_gaps.ipynb">2_with_gaps</a><br/><a href="https://github.com/Xeanst/NN_in_compling/blob/main/02_intro_to_nn/2_intro_to_neural_networks_no_gaps.ipynb">2_no_gaps</a></td>
  </tr>
  <tr>
    <td rowspan="2"><a href="https://github.com/Xeanst/NN_in_compling/tree/main/03_torch_mlp">3. Работа с тензорами и реализация персептрона</a></td>
    <td rowspan="2"><ul>
  <li>Использование библиотеки PyTorch</li>
  <li>Тензоры и операции над ними: создание и индексирование, изменение размера, конкатенация, поэлементные операции, операции сравнения</li>
  <li>Скачивание и подготовка данных</li>
  <li>Реализация многослойного персептрона</li>
</ul>  </td>
    <td><a href="https://teach-in.ru/lecture/2023-11-29-Studenikina">Лекция 4</a></td>
    <td><a href="https://github.com/Xeanst/NN_in_compling/blob/main/03_torch_mlp/3a_torch_mlp_with_gaps.ipynb">3a_with_gaps</a><br/><a href="https://github.com/Xeanst/NN_in_compling/blob/main/03_torch_mlp/3a_torch_mlp_no_gaps.ipynb">3a_no_gaps</a></td>
  </tr>
  <tr>
    <td><a href="https://teach-in.ru/lecture/2023-12-13-Studenikina">Лекция 5</a></td>
    <td><a href="https://github.com/Xeanst/NN_in_compling/blob/main/03_torch_mlp/3b_torch_mlp_with_gaps.ipynb">3b_with_gaps</a><br/><a href="https://github.com/Xeanst/NN_in_compling/blob/main/03_torch_mlp/3b_torch_mlp_no_gaps.ipynb">3b_no_gaps</a></td>
  </tr>
  <tr>
    <td rowspan="2"><a href="https://github.com/Xeanst/NN_in_compling/tree/main/04_word_embeddings">4. Методы векторного представления слов на основе нейросетей</a></td>
    <td rowspan="2"><ul>
  <li>Векторные представления слов word embeddings</li>
  <li>Модель word2vec: её разновидности CBOW и skip-gram, подход negative sampling</li>
  <li>Модель fastText</li>
  <li>Использование предобученных векторных представлений в задачах классификации и кластеризации</li>
</ul>  </td>
    <td><a href="https://teach-in.ru/lecture/2023-12-27-Studenikina">Лекция 6</a></td>
    <td><a href="https://github.com/Xeanst/NN_in_compling/blob/main/04_word_embeddings/4a_word_embeddings_with_gaps.ipynb">4a_with_gaps</a><br/><a href="https://github.com/Xeanst/NN_in_compling/blob/main/04_word_embeddings/4a_word_embeddings_no_gaps.ipynb">4a_no_gaps</a></td>
  </tr>
  <tr>
    <td><a href="https://teach-in.ru/lecture/2024-01-24-Studenikina">Лекция 7</a></td>
    <td><a href="https://github.com/Xeanst/NN_in_compling/blob/main/04_word_embeddings/4b_word_embeddings_with_gaps.ipynb">4b_with_gaps</a><br/><a href="https://github.com/Xeanst/NN_in_compling/blob/main/04_word_embeddings/4b_word_embeddings_no_gaps.ipynb">4b_no_gaps</a></td>
  </tr>
  <tr>
    <td><a href="https://github.com/Xeanst/NN_in_compling/tree/main/05_rnn">5. Архитектуры рекуррентных нейронных сетей</a></td>
    <td><ul>
  <li>Архитектура рекуррентной нейронной сети: алгоритм обратного распространения ошибки сквозь время, взрывающийся и затухающий градиент</li>
  <li>Виды RNN: один к одному, один ко многим, многие к одному, многие ко многим</li>
  <li>Архитектура сети долгой краткосрочной памяти LSTM</li>
</ul>  </td>
    <td><a href="https://teach-in.ru/lecture/2024-01-31-Studenikina">Лекция 8</a></td>
    <td><a href="https://github.com/Xeanst/NN_in_compling/blob/main/05_rnn/5_rnn_architecture_with_gaps.ipynb">5_with_gaps</a><br/><a href="https://github.com/Xeanst/NN_in_compling/blob/main/05_rnn/5_rnn_architecture_no_gaps.ipynb">5_no_gaps</a></td>
  </tr>
  <tr>
    <td><a href="https://github.com/Xeanst/NN_in_compling/tree/main/06_language_modeling">6. Языковое моделирование с помощью рекуррентных нейронных сетей</a></td>
    <td><ul>
  <li>Задача языкового моделирования</li>
  <li>Использование векторных представлений букв (символов) и токенов (слов)</li>
  <li>Генерация текста</li>
</ul>  </td>
    <td><a href="https://teach-in.ru/lecture/2024-02-07-Studenikina">Лекция 9</a></td>
    <td><a href="https://github.com/Xeanst/NN_in_compling/blob/main/06_language_modeling/6_language_modeling_with_gaps.ipynb">6_with_gaps</a><br/><a href="https://github.com/Xeanst/NN_in_compling/blob/main/06_language_modeling/6_language_modeling_no_gaps.ipynb">6_no_gaps</a></td>
  </tr>
   <tr>
    <td><a href="https://github.com/Xeanst/NN_in_compling/tree/main/07_attention">7. Архитектура sequence-to-sequence и механизм внимания</a></td>
    <td><ul>
  <li>Обобщенный механизм внимания</li>
  <li>Архитектура базовой модели seq2seq: энкодер и декодер</li>
  <li>Применение механизма внимания для seq2seq</li>
  <li>Задача машинного перевода</li>
</ul>  </td>
    <td><a href="https://teach-in.ru/lecture/2024-02-28-Studenikina">Лекция 10</a></td>
    <td><a href="https://github.com/Xeanst/NN_in_compling/blob/main/07_attention/7_seq2seq_attention.ipynb">7</a></td>
  </tr>
   <tr>
    <td><a href="https://github.com/Xeanst/NN_in_compling/tree/main/08_transformer">8. Архитектура Трансформер</a></td>
    <td><ul>
  <li>Архитектура энкодера и декодера без рекуррентных сетей</li>
  <li>Внутреннее внимание и множественное внимание</li>
  <li>Кодирование позиции, параллельная обработка элементов последовательности</li>
  <li>Остаточное соединение, нормализация по слоям</li>
</ul>  </td>
    <td><a href="https://teach-in.ru/lecture/2024-03-13-Studenikina">Лекция 11</a></td>
    <td><a href="https://github.com/Xeanst/NN_in_compling/blob/main/08_transformer/8_transformer_with_gaps.ipynb">8_with_gaps</a><br/><a href="https://github.com/Xeanst/NN_in_compling/blob/main/08_transformer/8_transformer_no_gaps.ipynb">8_no_gaps</a></td>
  </tr>
  <tr>
    <td rowspan="2"><a href="https://github.com/Xeanst/NN_in_compling/tree/main/09_bert"> 9. Языковая модель BERT</a></td>
    <td rowspan="2"><ul>
  <li>Модели ELMo: контекстуализированные векторы и задача языкового моделирования</li>
  <li>Модель BERT: энкодер трансформера, маскированное языковое моделирование, предсказание следующего предложения</li>
  <li>BPE-токенизация и WordPiece</li>
  <li>Библиотека Transformers от Hugging Face</li>
  <li>Использование предобученных векторов в других задачах</li>
</ul>  </td>
    <td><a href="https://teach-in.ru/lecture/2024-03-27-Studenikina">Лекция 12</a></td>
    <td><a href="https://github.com/Xeanst/NN_in_compling/blob/main/09_bert/9a_bert_with_gaps.ipynb">9a_with_gaps</a><br/><a href="https://github.com/Xeanst/NN_in_compling/blob/main/09_bert/9a_bert_no_gaps.ipynb">9a_no_gaps</a></td>
  </tr>
  <tr>
    <td><a href="https://teach-in.ru/lecture/2024-04-24-Studenikina">Лекция 13</a></td>
    <td><a href="https://github.com/Xeanst/NN_in_compling/blob/main/09_bert/9b_bert_with_gaps.ipynb">9b_with_gaps</a><br/><a href="https://github.com/Xeanst/NN_in_compling/blob/main/09_bert/9b_bert_no_gaps.ipynb">9b_no_gaps</a></td>
  </tr>
   <tr>
    <td><a href="https://github.com/Xeanst/NN_in_compling/tree/main/10_gpt">10. Генеративные предобученные трансформеры</a></td>
    <td><ul>
  <li>Четыре поколения GPT</li>
  <li>Гиперпараметры генерации: температура, top-k, top-p</li>
  <li>Принцип обучения с подкреплением с обратной связью от человека</li>
</ul>  </td>
    <td><a href="https://teach-in.ru/lecture/2024-05-08-Studenikina">Лекция 14</a></td>
    <td><a href="https://github.com/Xeanst/NN_in_compling/blob/main/10_gpt/10_gpt.ipynb">10</a></td>
  </tr>
</table>
</html>
