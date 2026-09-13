<h1 align="center">Medical Service Review Dataset</h1>

<big>This dataset is designed for training and evaluating sentiment analysis and opinion classification algorithms. It can also be useful for other natural language processing (NLP) tasks.</big>

<br>

<h3><b><i>General Information</i></b></h3>

  - Language of texts: Russian.
  - Data source: open sources.
  - Text feature: the authors' original punctuation is preserved.
  - Storage format: XML.
  - Review sentiment was determined based on the authors' ratings.
  - Only reviews with ratings of “1” and “5” were selected for inclusion in the dataset.
  - Reviews with a rating of “1” are labeled as negative, and reviews with a rating of “5” are labeled as positive.

<br>

<h3><b><i>Annotation Attributes</i></b></h3>

| Attribute | Description | Values |
| :---------: | :------------------------: | :------: |
| `text` | Comment text	| Text |
| `doc`	| Review of a doctor |	1 – yes, 0 – no |
| `service`	| Review of a service	| 1 – yes, 0 – no |
| `stars`	| Subjective rating given by the comment author	| In this dataset – 1 or 5 |
| `pos` |	Positive sentiment |	1 – yes, 0 – no |
| `neu`	| Neutral sentiment |	1 – yes, 0 – no |
| `neg` |	Negative sentiment |	1 – yes, 0 – no |
| `score` |	Aggregated sentiment based on pos, neu, and neg |	1 – positive, 0 – neutral, -1 – negative |
| `area` |	City where the medical institution is located |	spb – Saint Petersburg, msk – Moscow, ekb – Yekaterinburg, nsk – Novosibirsk |

<br>

<h3><b><i>Data Volume</i></b></h3>

***Training Set***
*File: dataset_of_medical_comments.xml*

  - Total reviews: 10,416
  - Negative: 5,230
  - Positive: 5,186


***Test Set***
*File: test_dataset_of_medical_comments.xml*

  - Total reviews: 1,363
  - Negative: 669
  - Positive: 694

<br>

<h3><b><i>Note</i></b></h3>

Since only reviews with author ratings of “1” and “5” were selected for the dataset, all included examples belong to either negative or positive sentiment. Neutral reviews are not represented in this selection.
