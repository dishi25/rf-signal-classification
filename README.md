##  RF-signal-classification
-Project Structure
```text
rf-signal-classification/
│
├── data/
│   ├── raw/
│   │   └── radioml/
│   │
│   ├── processed/
│   │
│   └── features/
│
├── models/
│   ├── saved_models/
│   └── checkpoints/
│
├── notebooks/
│
├── src/
│   │
│   ├── preprocessing/
│   │   ├── load_dataset.py
│   │   ├── normalize.py
│   │   └── denoise.py
│   │
│   ├── dsp/
│   │   ├── fft_processor.py
│   │   ├── spectrogram.py
│   │   └── filters.py
│   │
│   ├── feature_extraction/
│   │   ├── spectral_features.py
│   │   └── statistical_features.py
│   │
│   ├── ml/
│   │   ├── train.py
│   │   ├── evaluate.py
│   │   └── predict.py
│   │
│   ├── visualization/
│   │   ├── plot_fft.py
│   │   ├── confusion_matrix.py
│   │   └── spectrogram_view.py
│   │
│   └── utils/
│
├── main.py
├── requirements.txt
├── README.md
└── .gitignore
``` 