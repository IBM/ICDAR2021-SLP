# ICDAR 2021 Competition on Scientific Literature Parsing

Scientific literature contain important information related to cutting-edge
innovations in diverse domains. Advances in natural language processing have
been driving the fast development in automated information extraction from
scientific literature. But scientific literature are mainly in unstructured PDF
format. But while PDF is great for preserving the basic elements (characters,
lines, shapes, images, etc.) on a canvas for different operating systems or
devices for humans to consume, it’s not a format that machines can understand.

A critical challenge for automated information extraction from scientific
literature is that the documents often contain content that is not in natural
language, such as figures and table. Nevertheless, such content usually
illustrates key results, messages, or summarizations of the research. To obtain
a comprehensive understanding of scientific literature, the automated system
must be able to recognize the layout of the documents and parse the
non-natural-language content into a machine readable format. This competition
aims to drive the advances in the following two problems:

 - Document layout recognition
 - Table recognition

## Task A: Document layout recognition

 - Dataset: [PubLayNet](https://github.com/ibm-aur-nlp/PubLayNet)
 - Task: Identifying the position and category of document layout elements, including title, text, figure, table, and list.
 - Metric: [Mean Average Precision @ IoU 0.5:0.05:0.95](http://cocodataset.org/#detection-eval)
 - Participate: (LINK TO BE ADDED)


## Task B: Table recognition

 - Dataset: [PubTabNet](https://github.com/ibm-aur-nlp/PubTabNet)
 - Task: Converting table images into HTML code
 - Metric: [TEDS](https://github.com/ibm-aur-nlp/PubTabNet/tree/master/src)
 - Participate: (LINK TO BE ADDED)
