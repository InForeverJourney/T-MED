T-MED Dataset

T-MED is a teacher multimodal sentiment analysis dataset release (accepted to AAAI2026).
This release provides transcripts (text), extracted RoBERTa/HuBERT features, instructional information (subject & stage), and sentiment labels (8 classes).

Download
- Baidu Netdisk (CN mirror): v1:  https://pan.baidu.com/s/1viLRTNDrDU21AZVxfBwoww?pwd=2111  //  v2： https://huggingface.co/datasets/wangxiangren/T-MED/tree/main
  - Extraction code: 2111
- Version: v1.0 and v2.0

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
If you need the raw audio/video for further research, please contact the authors by email ( wangxr@mail.imu.edu.cn ).

Suggested information to include in your email:
- Name & affiliation
- Research purpose / intended use
- Which subset (or how much data) you need

Dataset License
Dataset License: CC BY 4.0 (recommended) or CC BY-NC 4.0 — see `DATA_LICENSE.txt`.

Citation
If the AAAI proceedings version is available, please cite the official AAAI publication.
Otherwise, please cite the arXiv preprint.

(Versioning Notes

The dataset is released in two versions with different feature granularities.

- v1.0 provides pooled, sample-level representations .
- v2.0 provides time-step-level representations with substantially larger storage requirements
  and is therefore distributed via an external link.)

Additional Release (Video Features):
We further release the extracted video features of T-MED through Baidu Netdisk: T-MED-video (Link: https://pan.baidu.com/s/1Q5ulFz4bRvu4Hpiqv_SxYw?pwd=2111
, Extraction code: 2111).
The video representations are extracted using a locally hosted HuggingFace-compatible VideoMAEv2-based video encoder, where each sample is processed from 16 uniformly sampled frames and converted into a fixed-dimensional representation by mean pooling the token-level features . The released file is organized at the sample level and includes the following fields: name, split, subject, subject_id, stage, stage_id, label, label_id, video_feat, and video_path. 
These video features are intended to be used together with the released text, audio, instructional, and label information for multimodal teacher sentiment analysis research.   


