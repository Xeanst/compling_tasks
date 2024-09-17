## Методы машинного обучения для решения задач компьютерной лингвистики

Данный курс призван сформировать практические навыки применения машинного обучения в задачах обработки текстов.

Он состоит из двух модулей, в каждом из которых будет подробна рассмотрена определенная задача компьютерной лингвистики: семантический модуль посвящен автоматическому распознаванию эмоций в тексте, синтаксический – автоматической оценке приемлемости предложений. Мы проанализируем, как данные задачи решаются в существующих исследованиях, разберем предложенные в статьях наборы данных и методы.

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
    <td colspan="4">А. Семантический модуль</td>
    </tr>
  <tr>
    <td rowspan="2"><a href="https://github.com/Xeanst/compling_tasks/tree/main/1_multiclass_emotion_detection">1. Многоклассовая классификация эмоций</a></td>
    <td rowspan="2"><ul>
  <li>Распознавание эмоций в тексте</li>
  <li>Загрузка и обработка данных</li>
  <li>Методы векторизации: мешок слов, TF-IDF</li>
  <li>Методы машинного обучения: наивный байесовский классификатор, логистическая регрессия, деревья решений, метод случайного леса</li>
  <li>Автоматический подбор параметров модели</li>
  <li>Оценка качества классификации</li>
</ul>  </td>
    <td>Лекция 1</td>
    <td><a href="https://github.com/Xeanst/compling_tasks/blob/main/1_multiclass_emotion_detection/1_multiclass_emotion_detection_with_gaps.ipynb">1_with_gaps</a><br/><a href="https://github.com/Xeanst/compling_tasks/blob/main/1_multiclass_emotion_detection/1_multiclass_emotion_detection_no_gaps.ipynb">1_no_gaps</a></td>
    </tr>
  <tr>
    <td>Лекция 2</td>
    <td><a href="https://github.com/Xeanst/compling_tasks/blob/main/1_multiclass_emotion_detection/1_multiclass_emotion_detection_with_gaps_continued.ipynb">1_with_gaps_continued</a><br/><a href="https://github.com/Xeanst/compling_tasks/blob/main/1_multiclass_emotion_detection/1_multiclass_emotion_detection_no_gaps.ipynb">1_no_gaps</a></td>
  </tr>
  <tr>
    <td rowspan="2"><a href="https://github.com/Xeanst/compling_tasks/tree/main/2_multilabel_emotion_detection">2. Многометочная классификация эмоций</a></td>
      <td rowspan="2"><ul>
  <li>Библиотека Datasets</li>
  <li>CEDR: Corpus for Emotions Detecting in Russian-language text sentences</li>
  <li>Baseline: словарь эмоциональной лексики</li>
  <li>Метод опорных векторов</li>
  <li>Ансамбль классификаторов</li>
  <li>Языковая модель ELMo</li>
  <li>Оценка качества классификации</li>
</ul>  </td>
    <td>Лекция 3</td>
        <td rowspan="2">2_with_gaps<br/>2_no_gaps</td>
    </tr>
  <tr>
    <td>Лекция 4</td>
     </tr>
     <tr>
  <td rowspan="2">3. Дообучение энкодерных моделей для распознавания эмоций</td>
      <td rowspan="2"><ul>
  <li>Языковая модель BERT</li>
  <li>Дистилляция знаний как метод ускорения нейронных сетей</li>
  <li>Дооучение ruBERT-tiny2 для распознавания эмоций</li>
  <li>Мультиязычная модель XLM-EMO для распознавания эмоций</li>
  <li>Применение XLM-EMO к корпусу CEDR</li>
  <li>Сравнение моноязычных и мультиязычных моделей</li>
</ul>  </td>
        <td>Лекция 5</td>
       <td>3_rubert_with_gaps<br/>3_rubert_no_gaps</td>
       </tr>
      <tr>
      <td>Лекция 6</td>
      <td>3_xlm_with_gaps<br/>3_xlm_no_gaps</td>
   </tr>
  <tr>
    <td colspan="4">Б. Синтаксический модуль</td>
    </tr>
  <tr>
  <td rowspan="2">4. Определение приемлемости предложений</td>
      <td rowspan="2"><ul>
  <li>Оценки приемлемости в лингвистике</li>
  <li>Корпус лингвистической приемлемости: источники данных, выбор явлений и разметка</li>
  <li>Бенчмарк GLUE и датасет CoLA для английского языка</li>
  <li>Наборы данных CoLA для русского и итальянского языков</li>
  <li>Дообучение BERT на CoLA с помощью Trainer</li>
  <li>Лингвистический анализ суждений о приемлемости</li>
</ul>  </td>
    <td>Лекция 7</td>
        <td rowspan="2">4_with_gaps<br/>4_no_gaps</td>
    </tr>
  <tr>
    <td>Лекция 8</td>
   </tr>
  <tr>
  <td rowspan="2">5. Топологический анализ данных для оценки приемлемости</td>
      <td rowspan="2"><ul>
  <li>Топологический анализ данных</li>
  <li>Компонента связности графа, простой цикл в графе</li>
  <li>Использование признаков TDA для классификации по приемлемости</li>
  <li>Метод главных компонент</li>
  <li>Определение весов признаков</li>
  <li>Определение и графическое отображение значимости голов внимания</li>
</ul>  </td>
    <td>Лекция 9</td>
        <td rowspan="2">5_with_gaps<br/>5_no_gaps</td>
    </tr>
  <tr>
    <td>Лекция 10</td>
   </tr>
  <tr>
  <td> 6. Соотношение приемлемости и вероятности</td>
      <td><ul>
  <li>Понятия "приемлемость" и "вероятность"</li>
  <li>Вероятность предложения для энкодерных моделей</li>
  <li>Определение приемлемости без дообучения для CoLA</li>
</ul>  </td>
    <td>Лекция 11</td>
    <td>6_with_gaps<br/>6_no_gaps</td>
   </tr>
</table>
</html>
