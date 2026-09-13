<h1 align="center">Medical Service Review Dataset</h1>

***Purpose***
This dataset is designed for training and evaluating sentiment analysis and opinion classification algorithms. It can also be useful for other natural language processing (NLP) tasks.

***General Information***
  - Language of texts: Russian.
  - Data source: open sources.
  - Text feature: the authors' original punctuation is preserved.
  - Storage format: XML.
  - Review sentiment was determined based on the authors' ratings.
  - Only reviews with ratings of “1” and “5” were selected for inclusion in the dataset.
  - Reviews with a rating of “1” are labeled as negative, and reviews with a rating of “5” are labeled as positive.

***Annotation Attributes***




| Attribute | Description | Values |
| :---------: | :------------------------: | :------: |
| text | Comment text	| Text |
| doc	| Review of a doctor |	1 — yes, 0 — no |
| service	| Review of a service	| 1 — yes, 0 — no |
| stars	| Subjective rating given by the comment author	| In this dataset — 1 or 5 |
| pos |	Positive sentiment |	1 — yes, 0 — no |
| neu	| Neutral sentiment |	1 — yes, 0 — no |
| neg |	Negative sentiment |	1 — yes, 0 — no |
| score |	Aggregated sentiment based on pos, neu, and neg |	1 — positive, 0 — neutral, -1 — negative |
| area |	City where the medical institution is located |	spb — Saint Petersburg, msk — Moscow, ekb — Yekaterinburg, nsk — Novosibirsk |


