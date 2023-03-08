# ScriptCorpus
Dialogue events collection derived from scripts of movies and dramas; for training and testing dialogue / chatbot systems


1. Basic statistics of dataset (For now. It is increasing now.) 
9,423 dialogue events
86,295 turns of speaking (a couple of utterances per turn) / 
18,848 speakers


2. Description of dataset
Conversation text data are in the two dataset folers (dataset_type1, 2), and their meta information are in the spreadsheet files (meta_character and meta_dialogueEvent). Both the character names and dialogue scenes are anonymised, so if necessary you need to link the texts and their meta information.

Dataset_type1: inclusive of context texts (지문)
Dataset_type2: exclusive of context texts
* All conversations are between two persons.
* Sometimes one of them says nothing but shows non-linguistic or paralinguistic expression. <move/> and <mute/> tags represent this type of expression. You can remove or keep them as you want.

Column names of text data files
* No: serial number
* serialID: individual scene indicator
* speaker: person who said ("context" means context text)
* dialogue: utterance(s) by the speaker

Column names of meta information file (meta_character)
* No: serial number
* serialID: individual scene indicator (match with the text data)
* speaker: person who said ("context" means context text) (match with the text data)
* gender: the gender of the speaker
* age: the age group of the speaker
* occupation: the job of the speaker

Column names of meta information file (meta_dialogeEvent)
* No: serial number
* serialID: individual scene indicator (match with the text data)
* scene_description: the (specific) places where the conversaion takes place
* place: the place where the conversaion takes place (categorised)
* purpose: for what the speakers converse (categorised). The mojority of the conversations has no specific purpose.
* othe_purpose: for what the speakers converse

