# [Lightweight Language Agnostic Data Sanitization Pipeline for Dealing with Homoglyphs in Code-Mixed Languages](https://www.springerprofessional.de/en/lightweight-language-agnostic-data-sanitization-pipeline-for-dea/27009748)

With the rise in hate speech on social media, numerous Natural Language Processing (NLP) techniques like text classification have been employed for detecting hate speech to make social media less toxic. However, hate speech users have started employing homoglyphs, which are characters that look identical to each other but have a different encoding or structure, to evade detection since most NLP models are trained on commonly recognized Unicode characters. In this paper we propose a novel lightweight language agnostic data sanitization pipeline which constitutes of a CNN for character level OCR followed by Symspell algorithm for candidate word generation and n-grams for word retrieval with the aim of retrieving dehomoglyphed sentences from homoglyphed sentences. We also introduce HEMNIST, an extended version of EMNIST that includes images of homoglyphs. We achieve a cosine similarity of 0.922, 0.845, 0.671, 0.508 and 0.231 between original and retrieved text at 5%, 10%, 20%, 30% and 50% masking respectively.


HEMNIST [Download](https://drive.google.com/file/d/173QXNAlfRlXYBaJE2M5dixJgngCbDPmp/view?usp=sharing)

![grid](https://github.com/user-attachments/assets/a652247b-f15f-4e00-ab04-4b3c75266da1)

Authors : Mohammad Yusuf Jamal Aziz Azmi, Subalalitha Chinnaudayar Navaneethakrishnan

Published in: Speech and Language Technologies for Low-Resource Languages

Publisher: Springer Nature Switzerland
