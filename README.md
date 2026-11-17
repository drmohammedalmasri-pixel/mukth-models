# mukth-models

Optional downloads for the Mukth Quran app (hifz mode).

Files are attached to the GitHub releases of this repository, not stored in git.

| Release | File | Size | SHA-256 |
|---|---|---|---|
| asr-v1 | mukth-asr-v1.zip | 99.4 MB | 37803b227d6b8323945fd9143fea7454ec9a909d6e3ff4e135f6152fb89e2d3f |

## Licence

The recitation model is adapted from NVIDIA FastConformer-Hybrid PCD Large (ar)
(https://huggingface.co/nvidia/stt_ar_fastconformer_hybrid_large_pcd_v1.0), licensed under
CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). Changes: encoder and CTC head only,
exported to ONNX, weights quantised to int8. See NOTICE.txt. No warranty.
