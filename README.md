# CaptureShelf models

Optional model files that the CaptureShelf app downloads on request from its Settings.

## DPDFNet-2 48 kHz (voice cleanup, "Enhanced")

Release `dpdfnet2-48k-v1` holds the three files of `DPDFNet2_48k.mlpackage`:

| Release asset | Path inside the package |
|---|---|
| `Manifest.json` | `Manifest.json` |
| `model.mlmodel` | `Data/com.apple.CoreML/model.mlmodel` |
| `weight.bin` | `Data/com.apple.CoreML/weights/weight.bin` |

DPDFNet-2 is by Ceva Inc. ([GitHub](https://github.com/ceva-ip/DPDFNet), [Hugging Face](https://huggingface.co/Ceva-IP/DPDFNet)), Apache License 2.0. This copy is converted to Core ML; see [NOTICE](NOTICE) for the changes and [LICENSE](LICENSE) for the licence.
