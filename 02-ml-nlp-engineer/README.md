# Gameglory · ML / NLP Engineer · «Похожие игры»

Тестовое задание на позицию ML / NLP Engineer (стажёр / джун) в проекте Gameglory, Bear Head Studio.
Нужно сделать поиск похожих игр двумя простыми подходами (коэффициент Жаккара по тегам и TF-IDF
по описаниям) и сравнить их на 50 размеченных парах.

Задание — в документе
[`Тестовое_задание_ML_NLP_Engineer.docx`](Тестовое_задание_ML_NLP_Engineer.docx).

## Состав пакета

| Путь | Что это |
|---|---|
| `Тестовое_задание_ML_NLP_Engineer.docx` | задание: задача, входные данные, что сделать, как сдать |
| `starter.ipynb` | шаблон ноутбука: загрузка данных, проверки, функции `show()` и `score_pairs()`, заготовки; выполняется «из коробки» |
| `similarity_eval_pairs.csv` | 50 размеченных пар (25 похожих и 25 непохожих, из них 10 «трудных») |
| `requirements.txt` | pandas, scikit-learn, jupyter; библиотеки для дополнительной части закомментированы |
| `../shared-data/` | синтетический датасет: `games.csv` (2000 игр), `reviews.csv`, `tags.csv`, описание полей `schema.md` |

## Как начать

```bash
python3 -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
jupyter lab starter.ipynb    # данные — из ../shared-data или $GAMEGLORY_DATA
```

Данные синтетические.
