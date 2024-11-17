## Учебный проект по пронозированию развития сердечно-сосудистых заболеваний
Заболеваемость и смертность от сердечно-сосудистых заболеваний (ССЗ) растет во всем мире на протяжении нескольких десятилетий. Машинное обучение дает возможность повысить точность прогнозирования рисков ССЗ.

Проект состосит из двух частей:
- теоретиическая: краткий обзор статьи (https://www.sciencedirect.com/science/article/pii/S2772442522000016);
- практическая: обучение модели машинного обучения для предсказания ССЗ.

## Обзор статьи
Статья посвящена разработке системы с использованием искусственного интеллекта (ИИ) для диагностики ССЗ. Авторы отдельно обращают внимание на использование алгоритмов машинного обучения в здравоохранении и описывают применение Python для достижения данной цели. Система использует различные техники, такие как логистическая регрессия и случайный лес. При использовании случайного леса точность на тренировочных данных составила около 83%.
В статье подробно обсуждается использование именно языка Python как оптимального для создания медицинских проектов, в том числе из-за множества бибилиотек (Pandas, SciPy, Matplotlib), простоты и надежности в использовании.
При разработке системы производился сбор данных, обработка количественных и категориальных переменных и использование алгоритмов для повышения точности прогнозов.
В статье рассматриваются такие модели, как случайный лес, деревья решений, алгоритм KNN и метод опорнных векторов SVM. Средии разобранных моделей наибольшую эффективность показал случайный лес.
Одой из ключевых особенностей системы является способность обрабатывать большие объемы медицинских данных.
Автоы подчеркивают, что использование алгоритмов машинного обучения могут увеличить эффективность медицинских исследований, улучшить качество медицинской помощи и ускорить процессы дианостики и лечения.
## Вывод:
Применение искусственного интеллекта и машинного обучения в здравоохранении является перспективным направлением, которое может значительно улучшить прогнозирование и диагностику заболеваний, а также повысить точность медицинских решений.


## Практическая часть
- датасет (ссылка https://www.kaggle.com/competitions/tech-weekend-data-science-hackathon/data);
- файл .ipynb с вычислениями;

## Используемые библиотеки
- pandas;
- numpy;
- seaborn;
- matplotlib;
- sk-learn;
- xgboost;
- tensorflow
