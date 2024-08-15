# MESC

[Source code and dataset of the paper Towards Multimodal Emotional Support Conversation Systems](https://arxiv.org/abs/2408.03650)

# Introduction
The Multimodal Emotional Support Conversation dataset (MESC) is enriched with comprehensive emotional support annotations across text, audio, and video modalities for mental health care. The MESC dataset is sourced from the TV show *In Treatment*, specifically from seasons 1 to 3. The series provides a detailed portrayal of the weekly sessions between psychotherapist Paul Weston and his patients, alongside his personal consultations with a therapist.

# Download the data
You can directly use the train, validation, and test sets for training your model, which contain the emotion clues extracted from both video and audio. If you prefer to extract emotion clues by yourself, you can refer to the `MESC.csv` file to obtain timestamps and download the raw videos from the website to process the multimodal data.

# Cite
If you use the MESC in a scientific publication, we would appreciate citations to the following paper:

```bibtex
@article{chu2024towards,
  title={Towards Multimodal Emotional Support Conversation Systems},
  author={Chu, Yuqi and Liao, Lizi and Zhou, Zhiyuan and Ngo, Chong-Wah and Hong, Richang},
  journal={arXiv preprint arXiv:2408.03650},
  year={2024}
}
