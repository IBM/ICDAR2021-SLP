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
language, such as figures and tables. Nevertheless, such content usually
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
 - [Participate](https://aieval.draco.res.ibm.com/challenge/41/overview)
 - Important dates:  
   * Open for submission: 20th July, 2020
   * Submission close: 31st March, 2021
   * Announcement of winning team: 1st May, 2021


## Task B: Table recognition

 - Dataset: [PubTabNet](https://github.com/ibm-aur-nlp/PubTabNet)
 - Task: Converting table images into HTML code
 - Metric: [TEDS](https://github.com/ibm-aur-nlp/PubTabNet/tree/master/src)
 - [Participate](https://aieval.draco.res.ibm.com/challenge/40/overview)
 - Important dates:  
   * Open for test submission: 20th July, 2020
   * Open for final evaluation submission: 28th March, 2021
   * Submission close: 31st March, 2021
   * Announcement of winning team: 1st May, 2021


## Terms and conditions
 - One team must be registered with one and only one account.
 - The maximum team size is 8 people.
 - Team mergers are NOT allowed.
 - This competition is open to every one, except to those who have a conflict of interest with the organizers.
 - Winning teams are strongly encouraged to release their code to help the community to reproduce their results and develop better models. If code cannot be released, winning teams must at least allow the organizers to reproduce their method and results for legitimacy verification.
 - For entries made by non-IBM employees IBM will make no claim to ownership of your entry or any intellectual property that it may contain. When submitting model source code, the code will be used for the sole purpose of verifying the legitimacy of the submission. Participants keep copyright to their code submissions.
 - It is allowed to use additional third-party data or pre-trained models for performance improvement.
 - Participants MUST NOT include human intervention in their method or take any manner to reverse engineer the ground truth of the test set, which will be treated as cheating and the participants will be banned to take part in this competition and future continuous competitions.
