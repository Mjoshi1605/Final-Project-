## Final-Project- Digital Voice Assistant (VISION)
### Abstract— 
#### Digital Assistance is computer program specially dedicated to assist user by responding to queries and performing basic tasks. It collects real time observations, which is use for better user experience and learn about the user's behavior. The digital assistant focuses at serving, the following most common and popular utilizations of digital assistant which are, question answering or information retrieval and implementing various local and/or remote services to perform tasks. Digital assistants make a use of advanced artificial intelligence (AI), natural language processing, natural language understanding, and machine learning to learn more about user and their environment in order to provide a personalized, chatty experience. The technologies require for digital voice assistant development are: Speech-To-Text (STT) And Text-To-Speech (TTS), Noise Control, Natural Language Processing (NLP), Natural Language Understanding (NLU), Natural Language Generation (NLG) and Deep learning. Digital assistant system uses microphone to capture the voice input of a user as a primary input. Users make use of a Microphone to capture the spoken input and a speaker to provide responses. The command block contains the main components to navigate the conversation of digital voice assistant with the user. ASR (Automatic speech recognition) is a method recognizer for speech, it forwards the recognition speculation to the NLU. A Natural Language Understanding (NLU) component can extract meaning as commands and associated entities from a pronouncement as text strings. Data providers obtain data using standard dataset from various sources for the better interaction. 
#### Keywords: Artificial Intelligence, machine learning, deep learning, NLP, NLU, Noise control
### INTRODUCTION 
#### Digital assistant is computer program designed to assist a user by answering questions and performing basic tasks. To interact with a digital assistant, must use a wake word, which device uses to activate the digital assistant. Digital assistant uses advanced Artificial Intelligence, natural language processing and understanding and machine learning. AI to learn as they go and provide a prenasalised, conservational communication. Combining historical information such as purchase preferences, home ownership, location, family size, so on, algorithms can create data models that identify patterns of behaviour and then refine those patterns as data is added. Existing examples of digital assistant are Apple’s Siri, Google assistant, Alexa etc. Digital assistant gathers real time insights, which business can use to continually improve the user’s experience and learn about their customers and employees
###  LITERATURE REVIEW 
####       Artificial Intelligence has been in great use when it comes to day-to-day life. Computer science defines AI research as the study of brilliant agents. In almost any direction one turns today, some form of computer-based information processing technology intrudes, whether to the individual knowingly or not. Artificial Intelligence (AI) has already changed our lifestyle. AI device that perceives its environment and takes actions that maximize its chance of successfully achieving its goals. Input to recommendation algorithm can be a database of user and items and output recklessly will be the recommendations. The user is the input into system by voice or text. This paper presents a new approach for smart search. Overall, in world there are many people who use assistant. The paper presents applications of virtual assistant and describes provocation of applying virtual assistant technology. It is a personalized python speech recognition project, which recognizes the user commands, interacts with them, and completes the tasks accordingly. For instance, it greets the user according to the time and event, plays music, reports the weather, and analyses the weather and suggests if it is okay for the user to go out today, opens all the system applications and folders, creates new folders and changes directories, sends emails and so on.

### 	VOICE ASSISTANT(VISION)

 First, Voice assistants are intelligent software that responds to voice commands and can run on any device, including smartphones, speakers, desktop/laptop computers, tablets, wearables, gaming consoles, TV consoles, virtual reality (VR) headsets, cars, and IoT devices. Examples include Amazon’s Alexa, Apple’s Siri, Google Assistant, and Microsoft’s Cortana.
This system is designed to be used efficiently on desktops. Personal assistant software improves user productivity by managing routine tasks of the user and by providing information from online sources to the user. VISION is effortless to use. Call the wake word ‘VISION’ followed by the command. And within seconds, it gets executed. Voice searches have dominated over text search. Virtual assistants are turning out to be smarter than ever. Allow your intelligent assistant to make email work for you. Detect intent, pick out important information, automate processes, and deliver personalized responses. This project was started on the premise that there is sufficient amount of openly available data and information on the web that can be utilized to build a virtual assistant that has access to making intelligent decisions for routine user activities
Artificial Intelligence

Artificial Intelligence (AI) has been propelled into the mainstream of learning. AI has many areas like computer science, cognitive and learning sciences, game design, psychology, sociology, philosophy, mathematics, neuroscience, linguistics, defence industry, medicine and education. AI uses logical series of steps called algorithms and advanced cognitive computing technologies to use the techniques of search and pattern matching for providing solutions for the demanded answers. AI is an interdisciplinary field that is used for diagnosis of illnesses, criminal identification and artificial instructions. To develop communication between human and computer, AI possesses the ability to reason while processing a natural language and has different scope of data in terms of the developments in the above mentioned fields. AI, has some other descriptions as well. AI has the ability to comprehend, learn, solve, interpret and execute complex mental process. AI is a subfield of computer science. Natural Language Processing (NLP) is provided for human computer interaction in order to combine human learning and machine reasoning [3 – 5]. NLP is the analysis of linguistic data, most commonly in the form of textual data such as documents or publications, using computational methods. 

#### A.	Technology used in Vision 
Vision uses Machine Learning technologies to function. Using ASR (Automatic speech recognition) to transcribe human speech (in this case, short utterances of commands, questions, or dictations) into text. Users speak natural language as voice commands in order to operate the mobile devices (all devices including phones, tabs) and its applications. The idea is to provide high level modelling primitives as integral part of a data model in order to facilitate the representation of real world situations and provide camera for more use of vision.camera in vision is basically used to detect motions and also recognize faces. It is also capable for authorization application.  
#### B.	System Architecture 

### The architecture of digital voice assistant (Vision)
 designed with 3 layers as follows:

1.Client layer

Clients enable the user to access the digital assistant via voice with the following characteristics.

•	Commonly Clients uses a microphone to capture the spoken input and a speaker is used to provide responses.

•	As an extension to this Clients may also capture input from a specific modality recognizer.
•	As an extension, Clients may also capture contextual information, e.g., location.
•	As an extension a client may also receive commands to be executed locally.
•	As an extension a client may also receive multimodal output to be rendered by a respective modality synthesizer.

2. Command Layer

This is service layer for a client to communicate with command management.
This layer has following characteristics:

•	The IPA service acts as an interface between the IPA client and the command management and provider selection service.
•	The output from the ASR is forwarded to the Provider Selection Service to get an appropriate meaning.
•	Alternatively, the Service may receive multimodal or text input from the client and forwards it directly to the Provider Selection Service to determine meaning.
•	Dialog Management receives recorded voice input from the Service and forwards it to the ASR
•	Dialog Management makes use of the TTS to generate audio data to be rendered on the Client
•	As an extension, it may also provide commands as output to be executed by the IPA Client
•	As an extension Dialogs may also return multimodal output or text to be rendered by a respective modality synthesizer on the Client.
•	The Dialog Manager is also responsible for a good user experience across the available Dialogs.
•	The Command Manager follows the principle to fill in all slots that are known before prompting the user for it.
•	The Command Manager also manages the session with a user. Conceptually, multiple sessions can be active in parallel. Commands are governed by Sessions, e.g., to free resources of ASR and NLU engines when a session expires.

•	Linguistic phenomena, like anaphoric references and ellipsis are expected to work within a Session. The selected Digital Voice Assistant Provider or the Command Manager may have leading roles for this task.

