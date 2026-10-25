# Ses modelleri ve lisansları / Voice models and licenses

Bu depodaki `ses-modelleri-v1` sürümü, MyMecMua uygulamasının kullandığı Piper (VITS) seslendirme modellerinin
bir kopyasını (ayna) içerir. Modeller [sherpa-onnx](https://github.com/k2-fsa/sherpa-onnx) dağıtımından alınmıştır
ve değiştirilmemiştir. Her ses, eğitildiği veri kümesinin lisansına tabidir.

This repository's `ses-modelleri-v1` release mirrors the Piper (VITS) text-to-speech models used by the MyMecMua app.
The files come unmodified from the [sherpa-onnx](https://github.com/k2-fsa/sherpa-onnx) distribution.
Each voice remains subject to the license of the dataset it was trained on.

| Lisans / License | Sesler / Voices |
|---|---|
| CC0 / kamu malı (public domain) | Türkçe Fettah ve Fahrettin (NabuCasa voice-datasets); Almanca Thorsten, Kerstin; Fransızca Gilles; Rusça Dmitri, Denis; Portekizce Tugão; İngilizce Joe (CC0), John, Kristin; İspanyolca Carl; Farsça Amir, Reza |
| CC BY 4.0 / CC BY 3.0 (kaynak belirtme / attribution) | Fransızca Siwis; İspanyolca Sharvard (University of Edinburgh); Kazakça Issai, Iseke, Raya |
| MIT | Urduca Fasih (model kartındaki beyana göre / per model card) |

## Notlar / Notes

- Piper ses modellerinin çoğu İngilizce *Lessac* sesinden ince ayarla türetilmiştir (model kartlarında
  "Finetuned from U.S. English lessac" yazar). Bu türetmenin lisans etkisi belirsizdir; ticari olmayan (NC) veya
  lisansı belirsiz sesler uygulamadan ve bu aynadan çıkarılmıştır.
  Most Piper voices are fine-tuned from the English *Lessac* voice; the licensing effect of that derivation is
  uncertain. Voices with non-commercial (NC) or unclear licenses were removed from the app and from this mirror.
- Kazakça sesler sıfırdan eğitilmiştir / The Kazakh voices were trained from scratch.
- Sesli dikte (konuşma tanıma) modelleri bu depoda **yoktur**; uygulama bunları Kroko ASR topluluk modellerinden
  (CC BY-SA 4.0, <https://huggingface.co/Banafo/Kroko-ASR>) indirir.
  Speech-recognition (dictation) models are **not** mirrored here; the app downloads Kroko ASR community models
  (CC BY-SA 4.0).
- Uygulama önce bu aynadan, olmazsa sherpa-onnx dağıtımından indirir / The app downloads from this mirror first
  and falls back to the sherpa-onnx distribution.

Sorun veya lisans bildirimi için / Issues or license notices: ilcandevs.ilcandevs@gmail.com — ILCANDEVS
