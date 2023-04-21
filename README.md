# Text Classifier
This is a simple ML for sorting texts and sentences into these categories:
  - atheism
  - christian
  - graphics
  - medicine
  - autos
  - motorcycles
  - baseball
  - hockey
  - electronics

## Metrics

```
                        precision    recall  f1-score   support

           alt.atheism       0.91      0.78      0.84       319
         comp.graphics       0.87      0.93      0.90       389
             rec.autos       0.96      0.93      0.94       396
       rec.motorcycles       0.94      0.97      0.96       398
    rec.sport.baseball       0.92      0.94      0.93       397
      rec.sport.hockey       0.93      0.98      0.95       399
       sci.electronics       0.90      0.83      0.87       393
               sci.med       0.96      0.88      0.91       396
soc.religion.christian       0.85      0.95      0.90       398

              accuracy                           0.91      3485
             macro avg       0.91      0.91      0.91      3485
          weighted avg       0.91      0.91      0.91      3485
```

## Confusion Matrix
![download](https://user-images.githubusercontent.com/68453992/233735490-b1e41ab1-b704-49c7-897d-b98317e46fea.png)<br>
or
```
        0   1   2   3   4   5   6   7   8
        |   |   |   |   |   |   |   |   |
0 - [[249   3   0   3   3   1   2   9  49]
1 -  [  4 363   1   1   6   0   9   1   4]
2 -  [  1   4 367   6   5   0  12   1   0]
3 -  [  1   1   7 385   3   0   1   0   0]
4 -  [  0   0   1   0 373  22   0   0   1]
5 -  [  0   1   0   0   5 392   0   0   1]
6 -  [  6  34   6   6   3   3 327   4   4]
7 -  [  6  10   0   7   6   4   7 347   9]
8 -  [  8   3   1   0   1   0   4   1 380]]
```

## To test new sentences, put them in the array:
![image](https://user-images.githubusercontent.com/68453992/233736086-ba5eeaae-b757-46c5-90f4-b6874479b064.png)

## Libraries
  - sklearn
  - matplotlib

