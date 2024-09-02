# Flirting Detection with Deep Learning

Authors: Wayne, Jae, Jerry

## Files Description

| Files    | Description |
| -------- | ------- |
| `Flirting_Detection_BERT.ipynb`  | BERT pipeline implementation to perform fine-tuning    |
| `Flirting_Detection_LSTM.ipynb` | Original implementation of LSTM pipeline, showed severe over-fitting with unsatisfactory accuracy     |
| `Flirting_Detection_LSTM_OPT.ipynb`    | Improved LSTM pipeline, with rigorous hyper-parameter tuning and data pre-processing    |

## Training

These 3 python notebook files can be run (e.g. on Google Colab) to train the corresponding models. Please see each file for more details on the usage and each step of training.

The dataset (used for training, validation, and testing) is a combination of `flirting_rated.csv` and a [public dataset](https://huggingface.co/datasets/ieuniversity/flirty_or_not) on Hugging Face. The code in the python notebook also takes care of preparing the combined dataset.

## Model Implementation Details

See [report](report.pdf).

## Download Trained Models

The trained models (by us) can also be downloaded here:

[LSTM](models/lstm/LSTM-Flirt.keras)

The LSTM model needs to be used with Keras API. See the `Flirting_Detection_LSTM.ipynb` for more details on how to load and use the trained model.

[BERT](https://drive.google.com/file/d/1txFkF6bgGMDcGBjQn-x7sRjFkidvJl23/view?usp=drive_link)

Similarly, the BERT model needs to be used with Hugging Face Transformers library. See the `Flirting_Detection_BERT.ipynb` on how to load and use the trained model.
