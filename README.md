T-MED Dataset

T-MED is a teacher multimodal sentiment analysis dataset release (accepted to AAAI2026).
This release provides transcripts (text), extracted RoBERTa/HuBERT features, instructional information (subject & stage), and sentiment labels (8 classes).

Download
- Baidu Netdisk (CN mirror): http://...
  - Extraction code: xxxx
- Version: v1.0
- SHA256: (to be added)

What is Included in This Release
This release provides **PKL files** containing:
- transcripts (text)
- extracted RoBERTa text features
- extracted HuBERT audio features
- instructional information (subject & stage)
- sentiment labels (8 classes)

Each sample contains:
- `id`: unique sample identifier
- `text`: transcript text
- `roberta_feature`: RoBERTa-based text feature
- `hubert_feature`: HuBERT-based audio feature
- `subject`: instructional subject
- `stage`: educational stage / grade level
- `label`: sentiment label (8 classes)

Raw Audio/Video (By Request)
If you need the raw audio/video for further research, please contact the authors by email.

Suggested information to include in your email:
- Name & affiliation
- Research purpose / intended use
- Which subset (or how much data) you need

Dataset License
Dataset License: CC BY 4.0 (recommended) or CC BY-NC 4.0 — see `DATA_LICENSE.txt`.

Citation
If the AAAI proceedings version is available, please cite the official AAAI publication.
Otherwise, please cite the arXiv preprint.

