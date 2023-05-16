# phashdaddy
Find Low Effort Phishing domains on godaddysites targeting your domain using perceptual hashing 

- add words to the phishWords.dict file to create a list of words to use for fuzzy domain creation
- change the word_lists list in the python file to words common in phishing targeting your company, leave it empty if you just wanna use the fuzzy domains from dnstwist
- add a list of known_images in the python script, make sure they're in the same directory as this script
- change line #48 to your own domain
