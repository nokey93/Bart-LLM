# Entwicklung eines BART-basierten Textzusammenfassungsmodells unter Verwendung CNN/DailyMail-Datasets


Dieses Projekt zielt darauf ab, ein fortgeschrittenes Modell für die Textzusammenfassung zu entwickeln, welches auf dem Transformer-basierten BART (Bidirectional and Auto-Regressive Transformers) Modell von Facebook aufbaut. Die Wahl fiel auf BART, da es in der Lage ist, Texte nicht nur effizient zu verarbeiten, sondern auch in kohärente, zusammenhängende Zusammenfassungen umzuwandeln, die den Kern und die Nuancen der Ursprungstexte bewahren. Um die Effektivität und Anwendbarkeit des Modells zu demonstrieren, wird dieses Projekt spezifische Datasets von CNN/DailyMail verwenden. Diese Datasets bieten eine reiche Quelle an journalistischen Texten, die sich ideal für das Training und die Evaluierung von Textzusammenfassungsmodellen eignen.

# Clone Modell von HuggingFace

```
# Load model directly
from transformers import AutoTokenizer, AutoModelForSeq2SeqLM

tokenizer = AutoTokenizer.from_pretrained("nokey93/bart_finetuned_cnn")
model = AutoModelForSeq2SeqLM.from_pretrained("nokey93/bart_finetuned_cnn")
```
