# balance_dataset
Dataset for political polarization study. More descriptions TBA.

Datasets
--------

* digg2010.tar.gz: Political articles from Digg, with digg user friendship data. __Note__: Dataset splitted to reduce size to under 100MB; join them by following https://www.tecmint.com/split-large-tar-into-multiple-files-of-certain-size/
* mturk.tar.gz: Political leaning labels from Mturk for a mixture of Digg and Reddit stories. Most articles have 4 labels; about 2000 articles have 20 labels per article.
* data2011.tar.gz: Political articles from Digg and Reddit (many of which are overlap in mturk.tar.gz).

Format
------
Each line is a JSON object.

References
----------

```
@inproceedings{zhou2011classifying,
  title={Classifying the Political Leaning of News Articles and Users from User Votes.},
  author={Zhou, Daniel Xiaodan and Resnick, Paul and Mei, Qiaozhu},
  booktitle={ICWSM},
  year={2011}
}
```
