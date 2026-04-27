# Dataset Information

This project uses the **Cats vs Dogs dataset** from TensorFlow Datasets.

##  Source

* Dataset: Cats vs Dogs
* Provided by: TensorFlow Datasets (TFDS)

## How to Load

The dataset is automatically downloaded using the following code:

```python
import tensorflow_datasets as tfds

(ds_train, ds_val), ds_info = tfds.load(
    'cats_vs_dogs',
    split=['train[:80%]', 'train[80%:]'],
    as_supervised=True,
    with_info=True
)
```

## Dataset Details

* Total Images: ~25,000
* Classes:

  * Cat (0)
  * Dog (1)

##  Note

The dataset is not stored in this repository due to its large size.
It will be downloaded automatically when running the notebook.
