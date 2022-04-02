# Hello_vmt
Video-guided machine translation display platform

And you can download the model from https://drive.google.com/xxx

run main.py and you can see the project like the one shown below .

<img src="https://github.com/Cathy-t/Hello_vmt/blob/main/vmt.gif" alt="show" />

## References
- https://github.com/kirbiyik/caption-it
- http://flask.pocoo.org/docs/1.0/deploying/
- https://github.com/Cathy-t/HELLO_image
- https://authors.elsevier.com/c/1eq-j3OAb95KRy
- https://d.wanfangdata.com.cn/patent/CN202110704424.6
- https://d.wanfangdata.com.cn/patent/CN202110395391.1

This is the PyTorch implementation of the paper: 
<font color=blue>Video-guided machine translation via dual-level back-translation. Shiyu Chen ,Yawen Zeng ,Da Cao and Shaofei Lu. Knowledge-Based Systems 2022.</font>

```
@article{CHEN2022108598,
title = {Video-guided machine translation via dual-level back-translation},
journal = {Knowledge-Based Systems},
volume = {245},
pages = {108598},
year = {2022},
issn = {0950-7051},
doi = {https://doi.org/10.1016/j.knosys.2022.108598},
url = {https://www.sciencedirect.com/science/article/pii/S0950705122002684},
author = {Shiyu Chen and Yawen Zeng and Da Cao and Shaofei Lu},
keywords = {Multiple modalities, Video-guided machine transaltion, Back-translation, Shared transformer},
abstract = {Video-guided machine translation aims to translate a source language description into a target language using the video information as additional spatio-temporal context. Existing methods focus on making full use of videos as auxiliary material, while ignoring the semantic consistency and reducibility between the source language and the target language. In addition, the visual concept is helpful for improving the alignment and translation of different languages but is rarely considered. Toward this end, we contribute a novel solution to thoroughly investigate the video-guided machine translation issue via dual-level back-translation. Specifically, we first exploit a sentence-level back-translation to obtain the coarse-grained semantics. Thereafter, a video concept-level back-translation module is proposed to explore the fine-grained semantic consistency and reducibility. Lastly, a multi-pattern joint learning approach is utilized to boost the translation performance. By experimenting on two real-world datasets, we demonstrate the effectiveness and rationality of our proposed solution.}
}
