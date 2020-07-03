# Welcome to Zhihang Xu(徐志航）'s Text-To-Speech Demo Page
**CONTACT me dazenhom#gmail.com or dazenhom666#sjtu.edu.cn**

## UNSUPERVISED TTS SPEAKER ADAPTATION USING X-VECTOR CONTROLLED PARAMETERS, Zhihang Xu, Bo Chen, Kai Yu (submitted to Interspeech2020)
- In this paper, we proposed a novel unsupervised adaptation method, which makes the TTS model parameters controlled by xvector.
- The experiments result shows that this can improve the similarity and naturalness especially on dirty unseen speakers.
- model introduction: we followed the Tacotron2 framework, and make the decoder LSTM to controlled by scaling the shifting vectors, whici are trained from xvector with the whole TTS model.
![Image](/pic/xvec/tacotron.png)
- Here give some audio samples
[demo page](/htmls/xvec-tts.html)


## Bo Chen, Kuan Chen , Zhijun Liu, Zhihang Xu, Songze Wu, Chenpeng Du, Muyang Li, Sijun Li, Kai Yu. “SJTU Entry in Blizzard Challenge 2019"
- In this chanllenge, to build a high speech quality with rich speaking styles, the TTS system is consist of "Front-end Text processor","Back-end Spectrum mode","Wavenet Vocoder" and "Bandwith Extender".
  - High level model view
![Image](/pic/bc2019/struc1.png)
<!-- 
- Back-end Spectrum model introction
![Image](/pic/bc2019/struc2.png)
-->
- Here we give some examples of speeches synthesized using test texts in difference types: 1 minute long talk show texts/ short spoken texts / Chinese poems
- [demo page](/htmls/bc2019.html)


## VAE based nonparallel voice conversion demo
- In this research, we apply [TCVAE](https://arxiv.org/pdf/1802.04942.pdf) into Voice conversion on Chinese corpus.
- Here we show the voice conversion among Chinese speakers and English speakers.
- [demo page](/htmls/vae-vc.html)


## F0 controlled Tacotron speech synthesis demo
- model introduction
![Image](/pic/f0/f0-struc.png)
- We use the F0 statistic feature(mean and std) of a small audio segment (from phone asr force alignment) to control the speech speaking style
- For inference, we use the text to predict the F0 statistic feature
- We can see the result that the speeches is controlled by F0 mean and std obviously.
  - mean controls the pitch level. [demo page](https://dazenhom.github.io/sjtu_tts_report/20181023/mean/mean.html)
  - std controls the speech variance to make the speech more excited or negative. [demo page](https://dazenhom.github.io/sjtu_tts_report/20181023/mean/mean.html)
