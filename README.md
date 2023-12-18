# Dark Patterns Recognition DarkDetect

Chrome extension that detects and highlights dark patterns on shopping websites. It reads text on product pages of shopping websites, then identifies and classifies dark pattern text. These potential dark patterns are then highlighted, with a popup that identifies and explains the category that a given dark pattern belongs to. 

train the classifier
page segmentation algorithm

## Tech Stack
The Chrome Extension front-end that scrapes the active web page is written in Javascript. For the back-end, a Python server running Streamlit interfaces Bernoulli Naive Bayes models to classify tokens of text sent to it.

## Reference
Mathur, A., Acar, G., Friedman, M. J., Lucherini, E., Mayer, J., Chetty, M., & Narayanan, A. (2019). Dark Patterns at Scale: Findings from a Crawl of 11K Shopping Websites. Proceedings of the ACM on Human-Computer Interaction, 3(CSCW), 81.
https://github.com/NicholasTung/dark-patterns-recognition
