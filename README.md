# ML on 5
Pet-проект (портфолио) для повышения навыков разработки ML|DL моделей 
и демонстрации данных навыков на типовых наборах данных (_titanic_, _housing_, etc.).

## 1. Структура ...
### 1.1. подпроекта
Каждая директория - отдельный набор данных с `csv`-файлами данных. 
В той же директории хранятся файлы JupyterNotebook (в названии файла - используемый алгоритм ML) и сохранёные модели расширения `.pkl`
Структура директории имеет следующий вид (на примере подпроекта _titanic_):
```
- titanic
--- models
------ model-first.pkl
------ ...
------ model-N.pkl
--- model-first.ipynb
--- ...
--- model-N.ipynb
```

### 1.2. данных
Выбор проектов для использования обусловлен необходимостью разнообразия изучаемых задач (бинарная|мультиклассовая классификация, регрессия).
Данные взяты с Kaggle-а:
* [titanic](https://www.kaggle.com/competitions/titanic)
* [housing](https://www.kaggle.com/competitions/boston-housing/)
* [cancer](https://www.kaggle.com/datasets/erdemtaha/cancer-data)
* [global emissions](https://www.kaggle.com/datasets/ashishraut64/global-methane-emissions)
* [space titanic](https://www.kaggle.com/competitions/spaceship-titanic)

### 1.3. скриптов
Каждый скрипт реализует один алгоритм ML-а (соответственно названию) и имеет простую структуру 
(подключение модулей, обучение, перекрёстная проверка, сохранение модели и т.п.).