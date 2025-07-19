# Entwicklung eines BART-basierten Textzusammenfassungsmodells unter Verwendung CNN/DailyMail-Datasets


Dieses Repository demonstriert, wie ein Textzusammenfassungsmodell auf Basis der BART-Architektur von Facebook trainiert werden kann. Als Trainings- und Evaluationsgrundlage dient das CNN/DailyMail-Dataset. Der Workflow ist im Jupyter Notebook `Text_Zusammenfassung.ipynb` dokumentiert und umfasst Datenvorbereitung, Fine-Tuning sowie die Generierung von Zusammenfassungen.

# Clone Modell von HuggingFace

## Voraussetzungen

```
- Python 3.8 oder neuer
- [PyTorch](https://pytorch.org/)
- [Transformers](https://huggingface.co/docs/transformers/index)
- [Datasets](https://huggingface.co/docs/datasets/index)
- Jupyter Notebook
```

## Notebook ausführen
Das Notebook `Text_Zusammenfassung.ipynb` führt Schritt für Schritt durch den Trainingsprozess. Es lädt das CNN/DailyMail-Dataset, bereitet die Texte vor und passt ein vortrainiertes BART-Modell an. Anschließend können eigene Texte zusammengefasst werden.
