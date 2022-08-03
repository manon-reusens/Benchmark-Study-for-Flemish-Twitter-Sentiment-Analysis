# Benchmark-Study-for-Flemish-Twitter-Sentiment-Analysis
This is the Github Repository with the code of the paper Benchmark Study for Flemish Twitter Sentiment Analysis (Reusens et al., 2022)

The experiments on the lexicon-based and traditional machine learning models were done using different types of preprocessing.
Here we provide some examples on the differences of the different approaches:


| Original Tweet                                                                     | Textified                                                  | Stemmed                                         | Lemmatized                                       |
|------------------------------------------------------------------------------------|------------------------------------------------------------|-------------------------------------------------|--------------------------------------------------|
| Het valt   echt nog op  en opnieuw voel ik mij uitgesloten                         | Het valt   echt nog op  en opnieuw voel ik mij uitgesloten | valt   echt opnieuw voel uitgeslot              | vallen echt opnieuw voelen uitsluiten            |
| Ik vind een @YouTube-video  leuk: https://t.co/uIbxaeasd5  Content Cop - Jake Paul | Ik vind een @YouTube-video  leuk: Content Cop - Jake Paul  | vind   youtube-video leuk  content cop jak paul | vinden youtube-video  leuk content cop jake paul |
