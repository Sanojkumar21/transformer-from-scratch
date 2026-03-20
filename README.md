# Raw Attention

PyTorch implementation of the Transformer architecture from "Attention Is All You Need" (Vaswani et al., 2017).

Trained on English → Hindi translation using the OPUS-100 dataset. Code is written to be explicit and readable  prioritizes understanding over performance.

## Dataset

OPUS-100 English-Hindi (`Helsinki-NLP/opus-100`)

- Tokenizer: BPE trained from scratch
- Special tokens: `[PAD]` `[SOS]` `[EOS]` `[UNK]`

## Setup
```bash
pip install -r requirements.txt
```

## License

MIT
