Репозиторий с материалами для курса "Методы машинного обучения для решения задач компьютерной лингвистики"

Данный курс призван сформировать практические навыки применения машинного обучения в задачах обработки текстов.

Он состоит из двух модулей, в каждом из которых будет подробна рассмотрена определенная задача компьютерной лингвистики: семантический модуль посвящен автоматическому распознаванию эмоций в тексте, синтаксический – автоматической оценке приемлемости предложений. Мы проанализируем, как данные задачи решаются в существующих исследованиях, разберем предложенные в статьях наборы данных и методы.

<!DOCTYPE html>
<html>
<table>
  <tr>
    <th>Тема</th>
    <th>Содержание</th>
  </tr>
  <tr>
    <td>1. Многоклассовая классификация эмоций</td>
    <td><ul>
  <li>Распознавание эмоций в тексте</li>
  <li>Загрузка и обработка данных</li>
  <li>Методы векторизации: мешок слов, TF-IDF</li>
  <li>Методы машинного обучения: наивный байесовский классификатор, логистическая регрессия, деревья решений, сетод случайного леса</li>
  <li>Автоматический подбор параметров модели</li>
  <li>Оценка качества классификации</li>
</ul>  </td>
  </tr>
  <tr>
    <td>2. Многометочная классификация эмоций</td>
      <td><ul>
  <li>Библиотека Datasets</li>
  <li>CEDR: Corpus for Emotions Detecting in Russian-language text sentences</li>
  <li>Baseline: словарь эмоциональной лексики</li>
  <li>Метод опорных векторов</li>
  <li>Ансамбль классификаторов</li>
  <li>Языковая модель ELMo</li>
  <li>Оценка качества классификации</li>
</ul>  </td>
     <tr>
     </tr>
  <td>3. Дообучение энкодерных моделей для распознавания эмоций</td>
      <td><ul>
  <li>Языковая модель BERT</li>
  <li>Дистилляция знаний как метод ускорения нейронных сетей</li>
  <li>Дооучение ruBERT-tiny2 для распознавания эмоций</li>
  <li>Мультиязычная модель XLM-EMO для распознавания эмоций</li>
  <li>Применение XLM-EMO к корпусу CEDR</li>
</ul>  </td>
   </tr>
  <tr>
  <td>4. Определение приемлемости предложений</td>
      <td><ul>
  <li>Оценки приемлемости в лингвистике</li>
  <li>Корпус лингвистической приемлемости CoLA</li>
  <li>Наборы данных CoLA для русского и итальянского языков</li>
  <li>Дообучение BERT на CoLA с помощью Trainer</li>
  <li>Лингвистический анализ суждений о приемлемости</li>
</ul>  </td>
   </tr>
  <tr>
  <td>5. Топологический анализ данных для оценки приемлемости</td>
      <td><ul>
  <li>Топологический анализ данных</li>
  <li>Использование признаков TDA для классификации по приемлемости</li>
  <li>Определение весов признаков</li>
  <li>Графическое отображение значимости голов внимания</li>
</ul>  </td>
   </tr>
  <tr>
  <td> 6. Соотношение приемлемости и вероятности</td>
      <td><ul>
  <li>Понятия "приемлемость" и "вероятность"</li>
  <li>Вероятность предложения для энкодерных моделей</li>
  <li>Определение приемлемости без дообучения для CoLA</li>
</ul>  </td>
   </tr>
</table>
</html>
