# Hiberno-English Audio Transcription Dataset
## Collection of Manually Transcribed Audio Samples from the Irish House of Representatives (Dáil Éireann).
<br>Some themes covered are the economy, environment, housing crisis, and education in Ireland. This dataset may be used by anyone wishing to test a speech-to-text transcription model on a dataset of many Irish accents in the English language. There are a large number of accents in the Republic of Ireland and therefore it is unlikely that all have been covered in this dataset. However, this serves as a good benchmark 

## Clip Selection
There are five clips selected from a representative of each constituency in the Republic of Ireland.
That is, 39 constituencies x 5 clips to make a total of 195 clips.
The clips are intentionally cut to ensure that the beginning and end of the sentence is not cut off, and thus the full reference transcription for each clip is represented in the audio.

## Transcription
Some rules were applied in order to standardise the transcription and thus make the evaluation (for example, WER) more accurate.<br>
These rules are as follows:
* All text is converted to lowercase
* Contractions are applied where possible (for example, "I will" to "I'll")
* Heifens are removed and joint words are separated (for example, "u-turn" becomes "u turn")
* Numbers are written in alphabetic form rather than numeric

Happy testing!
