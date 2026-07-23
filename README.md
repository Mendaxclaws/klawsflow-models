# KlawsFlow model assets

Pre-built on-device model archives downloaded by [KlawsFlow](https://klawsfx.com) at runtime. No application code lives here.

| Asset | Contents | License |
| --- | --- | --- |
| `sherpa-onnx-zipvoice-distill-int8-libritts.tar.bz2` | ZipVoice-distill (LibriTTS-trained) int8 ONNX export + Vocos vocoder + espeak-ng data, sherpa-onnx layout | Model: Apache-2.0 code, LibriTTS (CC BY 4.0) training corpus. Upstream: [k2-fsa/ZipVoice](https://github.com/k2-fsa/ZipVoice), [k2-fsa HF checkpoint](https://huggingface.co/k2-fsa/ZipVoice). Export process: one-time ONNX export of the official checkpoint. |

Vocoder `vocos_24khz.onnx` and `espeak-ng-data` are redistributed from [sherpa-onnx](https://github.com/k2-fsa/sherpa-onnx) releases (Apache-2.0).
