# A model to identify Manipulative Language

Our model will be released soon! 
[Stay in touch](mailto:diletta.goglia@it.uu.se?subject=IC2S2%20Poster&body=Hi%2C%0A%0AI%20saw%20your%20poster%20at%20IC2S2.%0ALet%27s%20keep%20in%20touch%20for%20updates%21) for updates.

[![Poster](ic2s2/poster_goglia.png)](ic2s2/poster_goglia.pdf)





## Directory structure
```
.
├── data/
│   ├── training_set.py
│   ├── test_set.py                               
│   └── youtube/                    #   'Supernanny' TV show episodes
│       ├── data_raw/               #   audio files of each episode (subdirs correspond to seasons)
│       ├── data_clean/             #   diarization (transcripts + VAD)
│       └── data_analysis/          #
├── models/                         #
├── img/
├── annotations/
│   ├── to_annotate/                # csv files, automatically generated
│   ├── llama3/                     # one csv per experiment 
│   ├── gpt4/                       # 
│   └── human-annotated/            # one csv file per annotator
├── src/
│   ├── __init__.py                 
│   ├── utilities.py
│   ├── youtube.py
│   ├── diarization.py
│   ├── generate_annot_files.py                    
│   ├── annot_agreement.py
│   ├── human_mach_comparison.py
│   ├── pseudolabeling.py
│   └── test.py             
├── requirements.txt
└── README.md
```
