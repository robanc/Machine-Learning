\# Module 8 — Deep Learning



DataTalks.Club Machine Learning Zoomcamp 2026



\## Lesson: TensorFlow/Keras



Notebook: `notebook.ipynb`



Topics: CNNs, Xception transfer learning, image augmentation, learning-rate experiments, fine-tuning, and evaluation.



Dataset: Clothing Dataset Small.



\## Homework: PyTorch CNN



Binary image classification: curly vs. straight hair.



\- PyTorch CPU

\- BCEWithLogitsLoss

\- SGD with momentum

\- 10 baseline epochs

\- 10 additional augmented epochs



\## Homework Answers



| Question | Answer |

|---|---|

| Q1 — Loss function | BCEWithLogitsLoss |

| Q2 — Parameters | 20,073,473 |

| Q3 — Median baseline accuracy | 0.81 |

| Q4 — Baseline loss standard deviation | 0.139 |

| Q5 — Mean augmented evaluation loss | 0.576 |

| Q6 — Last-five augmented evaluation accuracy | 0.72 |



\## Reproducing Homework Results



From the `homework` directory, install dependencies:



```powershell

pip install -r requirements-cpu.txt

```



Download and extract the homework dataset into `homework/data/`, then run:



```powershell

python reference\_train.py --data-dir data

```



Training histories are saved under `homework/runs/reference/` relative to the Module 8 directory.



Downloaded datasets, virtual environments, and model checkpoints are excluded from Git.

