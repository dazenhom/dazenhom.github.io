## Welcome to Zhihang Xu(徐志航）'s Text-To-Speech Demo Page
**CONTACT me dazenhom#gmail.com or dazenhom666#sjtu.edu.cn**
### UNSUPERVISED TTS SPEAKER ADAPTATION USING X-VECTOR CONTROLLED PARAMETERS, Zhihang Xu, Bo Chen, Kai Yu (submitted to Interspeech2020)
- model introduction
![Image](/pic/xvec/tacotron.png)

- audio demo
[demo page](/htmls/xvec-tts.html)

### Bo Chen, Kuan Chen , Zhijun Liu, Zhihang Xu, Songze Wu, Chenpeng Du, Muyang Li, Sijun Li, Kai Yu. “SJTU Entry in Blizzard Challenge 2019"
### Blizzard Challenge 2019 demo
- model introduction
```
![Image](/pic/bc2019/struc2.png)
```
![Image](/pic/bc2019/struc1.png)
- Here we give some examples of speeches synthesized using test texts in difference types: 1 minute long talk show texts/ short spoken texts / Chinese poems
- [demo page](/htmls/bc2019.html)

### VAE based nonparallel voice conversion demo
- Here we show the voice conversion among Chinese speakers and English speakers.
- [demo page](https://dazenhom.github.io/sjtu_tts_report/20181023/old_mean/mean.html)

### F0 controlled Tacotron speech synthesis demo
- model introduction
![Image](/pic/f0/f0-struc.png)
- We use the F0 statistic feature(mean and std) of a small audio segment (from phone asr force alignment) to control the speech speaking style
- For inference, we use the text to predict the F0 statistic feature
- We can see the result that the speeches is controlled by F0 mean and std obviously.
  - mean controls the pitch level. [demo page](https://dazenhom.github.io/sjtu_tts_report/20181023/mean/mean.html)
  - std controls the speech variance to make the speech more excited or negative. [demo page](https://dazenhom.github.io/sjtu_tts_report/20181023/mean/mean.html)

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/dazenhom/dazenhom.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
