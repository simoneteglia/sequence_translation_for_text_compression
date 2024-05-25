# sequence_translation_for_text_compression

This repository contains the code for a family of models that tries to zip a text file given in input.
The models are trained to predict the hexadecimal version of the zip, as explained in the image

![approach](images/approach.png)

## Performances with bart-large

| Model      | Short Sentences | Randomized Short Sentences | Medium Sentences |
| ---------- | --------------- | -------------------------- | ---------------- |
| bart-large | 87.45%          | 85.81%                     | 69.28%           |
