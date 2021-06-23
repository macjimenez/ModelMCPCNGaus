# DDIRelExtract
Extrae relaciones de corpus biomédico 

## How to run

You must give `--do_lower_case` option if pretrained model is uncased model.

```bash
$ python3 main.py 
```

## Results

`F1 score` on 4 Positive types (Mechanism, Effect, Advice, Int)

|                                           | F1 score |
| ----------------------------------------- | -----    |
| [BI-LSTM]                                 | 65.16    |
| [PCNN]                                    | 68.35    |
| [MCCNN]                                   | 70.70    |
| [MCPCNN]                                  | 71.74    |
| [MCPCNN+Att+Gauss]                        | **73.82**|
