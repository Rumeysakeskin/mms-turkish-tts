This repository contains the **Turkish (tur)** language text-to-speech (TTS) model checkpoint.

This model is part of Facebook's [Massively Multilingual Speech](https://arxiv.org/abs/2305.13516) project, aiming to provide speech technology across a diverse range of languages. You can find more details about the supported languages and their ISO 639-3 codes in the [MMS Language Coverage Overview](https://dl.fbaipublicfiles.com/mms/misc/language_coverage_mms.html), and see all MMS-TTS checkpoints on the Hugging [Face Hub: facebook/mms-tts](https://huggingface.co/models?sort=trending&search=facebook%2Fmms-tts).

### Running MMS-TTS inference in Colab

In [this notebook](https://github.com/Rumeysakeskin/mms-turkish-tts/blob/main/facebook_mms_tts_turkish.ipynb), we give an example on how to run Turkish text-to-speech inference using MMS TTS models.

By default, we run inference on a GPU. 

1. Installs necessary python packages for the other sections.
2. Choose a language or and download Turkish checkpoint. (Find the ISO code for your target language [here](https://dl.fbaipublicfiles.com/mms/tts/all-tts-languages.html).)
3. Load the checkpoint.
3. Specify the sentence you want to synthesize and generate the audio.

IT'S DONE!!

[Download Audio](https://store10.gofile.io/download/web/cb5de95e-2c23-4301-b013-2c06f6ba7278/download.wav)
