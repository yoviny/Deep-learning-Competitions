![Bengali.AI logo](https://github.com/yoviny/Deep-learning-Competitions/blob/master/Bengali.Ai%20classification%20challenge/bengali%20logo.jpg)
# Bengali.AI Handwritten Grapheme Classification (20/12/2019 - 17/03/2020)

**Competition leaderboard ranking - 59/2059 (top 3%)**

Bengali is the 5th most spoken language in the world with hundreds of million of speakers. It’s the official language of Bangladesh and the second most spoken language in India. Considering its reach, there’s significant business and educational interest in developing AI that can optically recognize images of the language handwritten. This challenge hopes to improve on approaches to Bengali recognition.

![image](https://github.com/yoviny/Deep-learning-Competitions/blob/master/Bengali.Ai%20classification%20challenge/image.png)

Optical character recognition is particularly challenging for Bengali. While Bengali has 49 letters (to be more specific 11 vowels and 38 consonants) in its alphabet, there are also 18 potential diacritics, or accents. This means that there are many more graphemes, or the smallest units in a written language. The added complexity results in ~13,000 different grapheme variations (compared to English’s 250 graphemic units).

Bangladesh-based non-profit Bengali.AI is focused on helping to solve this problem. They build and release crowdsourced, metadata-rich datasets and open source them through research competitions. Through this work, Bengali.AI hopes to democratize and accelerate research in Bengali language technologies and to promote machine learning education.

For this competition, you’re given the image of a handwritten Bengali grapheme and are challenged to separately classify three constituent elements in the image: grapheme root, vowel diacritics, and consonant diacritics.
[source:https://www.kaggle.com/c/bengaliai-cv19/overview/description]

# Evaluation metric
Submissions are evaluated using a hierarchical macro-averaged recall. First, a standard macro-averaged recall is calculated for each component (grapheme root, vowel diacritic, or consonant diacritic). The final score is the weighted average of those three scores, with the grapheme root given double weight.
[source:https://www.kaggle.com/c/bengaliai-cv19/overview/evaluation]
