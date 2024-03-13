# Meaningful-system-development-using-the-TORGO-dataset-for-dysarthric-ASR

**Jinda Zhang**, Marcarious Hui, Aanchan Mohan

### Abstract

The TORGO dataset, originally developed for speech assessment, remains popular since it contains sentence and word level prompts from dysarthric speakers. The significant overlap in prompts between speakers does not allow for the development and evaluation of post-processing methods to improve dysarthric ASR. Our study contributes a protocol for data-selection using a linear programming algorithm. Cross-lingual representations using the wav2vec2-xlsr-53 provide a strong baseline on the original dataset. After accounting for prompt overlap, our results show the impact of removing prompt overlap on ASR performance. Furthermore, the impact of language models trained on out-of-domain text from the Librispeech and the Europarl corpus is presented. For further development, our results motivate a community-focused approach to data collection for word and sentence level prompts. To enable this outcome, our work introduces a new open-source application called VoiceCollector. 
