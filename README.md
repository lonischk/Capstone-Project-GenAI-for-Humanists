# UE-GenAI-for-Humanists
## Capstone Project - Pitch 

### Working title
Sherds in Conversation: A Local Dialogue Assistant for Pottery Identification

### Theme and Question
Archaeological pottery is identified by features such as firing, temper, hardness, surface treatment, and manufacturing technique. This knowledge is scattered across typologies and excavation reports and is hard for beginners to access. My question: can an AI assistant guide users through targeted questions about a ceramic's characteristics and, drawing on open-access literature, suggest plausible ware types, and where does such text-based identification reach its limits? The topic matters to me because I studied archaeology, and pottery identification is a classic case where expert knowledge is well documented but hard to query.

### The material
Open-access typologies, ware descriptions, and excavation publications on [period/region, e.g. Roman provincial pottery or medieval pottery in eastern Austria], covering roughly 5 to 10 ware types, prepared as short, consistently structured documents with source and license information. Likely gaps include poorly published regions and periods as well as literature that is not openly accessible. The material therefore reflects the perspective of published research.

### Why AI? 
A language model can hold a dialogue, take feature descriptions in everyday language, and match them against ware descriptions (RAG). Without AI, one would have to work through identification keys by hand. Risk: the model may confuse ware types, invent features, or sound overconfident. For this reason the system shows its source with every answer, offers several candidates rather than one "solution," and refers to experts for final identification.

### Who is it for? 
Archaeology students, volunteers at museums and excavations, and interested people looking for first orientation on finds.

### Team 
Individual project. Archaeological background and basic Python/data-preparation skills

### Concerns
Text descriptions cannot replace handling and seeing a sherd. Technically: small local models sometimes follow sources poorly. Ethically: results must stay labeled as suggestions, so that no one misclassifies finds or adopts wrong dates.
