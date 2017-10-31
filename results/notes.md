




# data
- Chlorine Data Set <http://www.cs.ucr.edu/~eamonn/time_series_data/>
    - # classes                     : 3
    - # samples in training set     : 467
    - # samples in testing set      : 3840
    - time series length            : 166

**Observed**
- 3445 samples
- batch_size: 30

## Validation:

### X
- 431, 166

### Y
- 431
* **This means that each sequence has only a single output class**, _rather than each sequence **step** having an output class_

val shapes< X:(431, 166) Y:(431,) > batch_size: 30
val BATCH shapes< X:(30, 166) Y:(30,) > batch_size: 30
At     1/ 3000: COST 1.189/1.855(1.103) -- Acc 0.267/0.500(0.004)
val shapes< X:(431, 166) Y:(431,) > batch_size: 30
val BATCH shapes< X:(30, 166) Y:(30,) > batch_size: 30
At   101/ 3000: COST 1.005/1.067(1.077) -- Acc 0.567/0.500(0.334)
Trained 1.0 epochs, accuracy is 0.500 and cost is 1.067