# Sanskrit diffusion

## Overview
In this project, we explored the generation of symbols using diffusion models, inspired
by prior work on generating Chinese characters shown by our professor at Vizuara Labs. We selected Sanskrit as the target
language, constructed a dataset of PNG images representing its charactersincluding
vowels , consonants , and their barakhadi combinationsand trained a diffusion model
to generate new Sanskrit symbols. This report details the methodology, experiments, and
findings.

## Selected Language: Sanskrit
Sanskrit is an ancient Indo-Aryan language known for its precise phonetics and grammar.
It contains a rich set of symbols including vowels , consonants , and their barakhadi forms.
I selected Sanskrit due to:
• Its structured and diverse character set
• Cultural and historical significance
• Potential application in linguistic preservation and digital script generation

## Dataset Preparation
• Total characters: 487  including standalone vowels, consonants, and their com-
binations.
• Image resolution: 128x128 pixels (RGB).
• Format: PNG.
• Source: Characters were generated from Devanagari Unicode using Python

## Results
> The diffusion model performs well on Sanskrit due to its clear structure, where swar
(vowels) and vyanjan (consonants) serve as the fundamental building blocks of words.
This structured nature, combined with well-defined grammatical rules, helps the model
learn and generate symbols more effectively.
Since Sanskrit has a relatively well-defined alphabet and grammatical structure, the
model can capture these patterns more accurately, leading to high-quality results in
symbol generation and recognition. This structure allows the model to focus on distinct
phonetic units, which enhances its ability to generate or recognize symbols with greater
precision.

![image](https://github.com/user-attachments/assets/40f3322f-c682-4d1b-a2ec-8cbfd912f287)


- Generated Symbol (GIF)
  https://jumpshare.com/v/h8E6bxYzl7eMiYD5i8ri


### Implemented by :
- Manjiri C
- Mansi Borle
  
