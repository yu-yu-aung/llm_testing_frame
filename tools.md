### tools

| Component | Recommended starting tool | Purpose |
|-----------|---------------------------|---------|
| Execution environment | Google Colab | Run your quantized models on the available GPU |
| Model loading | Transformers + bitsandbytes | Load and generate responses from Hugging Face models |
| Test dataset | JSONL | Store prompts, expected results, and scoring rules |
| Output validation | Python json + Pydantic | Validate JSON syntax, fields, and types |
| Framework tests | pytest | Check that your runner and scorers work correctly |
| Results analysis | pandas | Summaries and model comparisons |
| Result storage | JSONL + CSV | Preserve full responses and export tables |
| Version control | GitHub | Track code, prompts, datasets, and configurations |
| Dashboard—later | Streamlit | Browse comparisons and failed responses |