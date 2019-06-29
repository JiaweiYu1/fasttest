# fasttext

对paper：Bag of Tricks for Efficient Text Classification进行复现，使用AG，DBP，YELP_P三个dataset， 总结如下：



```markdown
|                             |    AG   |  TDBP  |  YELP_P  |
| ------------- --------------| --------|--------|----------|
| Test accuracy(h=10) bigram  |   92.5  |  98.6  |   95.7   |
| Time per epoch              |   1s    |  2s    |   3s     |
|                             |         |        |          |
| My result                   |         |        |          |
| Test accuracy(h=10) bigram  |   92.7  |  98.7  |   95.3   |
| Time per epoch              |   8s    |  114s  |   102s   |
```
