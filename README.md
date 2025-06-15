---
dataset_info:
  features:
  - name: tokens
    sequence: string
  - name: tags
    sequence:
      class_label:
        names:
          0: O
          1: B-Disease
          2: I-Disease
        id:
        - 0
        - 1
        - 2
  - name: sentence_id
    dtype: string
  splits:
  - name: test
    num_bytes: 2614997
    num_examples: 5737
  - name: train
    num_bytes: 6947635
    num_examples: 15488
  download_size: 1508920
  dataset_size: 9562632
---
