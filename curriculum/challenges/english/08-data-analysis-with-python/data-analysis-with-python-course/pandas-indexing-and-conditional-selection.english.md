---
id: 5e9a093a74c4063ca6f7c159
title: Pandas Indexing and Conditional Selection
challengeType: 11
isHidden: false
videoId: -ZOrgV_aA9A
---

## Description

<section id='description'>
<em>Instead of using notebooks.ai like it shows in the video, you can use Google Colab instead.</em>

More resources:

- <a href="https://github.com/ine-rmotr-curriculum/freecodecamp-intro-to-pandas" target="_blank" rel="noopener noreferrer">Notebooks on GitHub</a>
- <a href="https://colab.research.google.com/github/googlecolab/colabtools/blob/master/notebooks/colab-github-demo.ipynb" target="_blank" rel="noopener noreferrer">How to open Notebooks from GitHub using Google Colab.</a>

</section>

## Tests

<section id='tests'>

````yml
question:
  text: |
    What will the following code print out?

    ```py
    import pandas as pd

    certificates_earned = pd.Series(
        [8, 2, 5, 6],
        index=['Tom', 'Kris', 'Ahmad', 'Beau']
    )

    print(certificates_earned[certificates_earned > 5])
    ```

  answers:
    - |
      ```
      Tom      True
      Kris     False
      Ahmad    False
      Beau     True
      dtype: int64
      ```
    - |
      ```
      Tom      8
      Ahmad    5
      Beau     6
      dtype: int64
      ```
    - |
      ```
      Tom      8
      Beau     6
      dtype: int64
      ```
  solution: 3
````

</section>
