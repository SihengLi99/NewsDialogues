# NewsDialogues
ACL'2023 (Findings): NewsDialogues: Towards Proactive News Grounded Conversation

# Dataset
- All the conversation data files are in the 'dataset' folder, where the train/valid/test files are the splits used in our experiments.
- Each conversation includes:
  - news: the grounded news article during conversation
    - title: the tile of the news article
    - date: the date of the news article
    - url: the link to the news article
  - topics: key topics of the news written by human annotators
  - dialog: news grounded conversation, including agent and user utterances
    - user 
      - utterance
      - act: dialog act
    - agent
      - utterance
      - act: dialog act
      - topic: the target topic of this utterance
      - span: the grounded knowledge spans of this utterance
      - unanswerable: whether this utterance is an answer for unanswerable question
