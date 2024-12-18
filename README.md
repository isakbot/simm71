# simm71
To do:
-Iterate on RQ, possibly remove names and other noise in txt files
-look at the nlp1_lab notebook to see if i can move some of these code sections into my main notebook

for seminar: one data viz, like a graph, telling a story about the paper
DONE:
RQ
population
sampling
preprocessing (data cleaning and structuring) 
quick and dirty (since the context window is limited) exploratory narrative analysis using ChatGPT and sentence-based text data ("Act as a NLP expert who's analyzing this text corpus consisting of 11 different 'video model announcements' and perform all the steps required for narrative analysis" with subsequent prompts) and then token-based text data to compare the analyses.

Some of the most interesting and worthy output I receive is based on the following, with minor clarifications from my side:

/The overarching narrative is one of measured (in the sense of objective reasoning) technological progress and transformative potential. 
. Immersive and Visualization-Oriented Narratives
The Visualization theme features prominently, focusing on terms like "image," "effects," and "world." This suggests that the announcements aim to captivate audiences by emphasizing the visual and experiential possibilities of these technologies.
References to simulators and immersive experiences support a narrative of creating transformative, interactive environments.
. Balanced Tone: Optimistic Yet Informative
Sentiment analysis reveals a moderately positive tone, with announcements blending enthusiasm about future possibilities with a degree of objectivity to retain credibility.
The polarity and subjectivity scores suggest the announcements are carefully crafted to inspire confidence without appearing overly speculative. (A finding contrary to common-sensical expectations of direct promotional language)
. Subtle Future Aspirations
The Future Aspirations theme, though least represented, aligns with visionary elements in the text. Mentions of "future" and "new" suggest that the announcements touch on forward-looking ideas, albeit without making them the core focus. Temporal references, such as "new" and "future," are used to frame the announcements as steps toward progress.
. Framing of Use Cases
Recurrent mentions of practical applications such as movies, simulators, and games frame the narrative around tangible impacts on industries. This positioning reinforces the utility of the technology, connecting it to real-world scenarios.
Final Insights:
The corpus strategically balances positivity and factuality, emphasizing key areas like technological advancements and immersive visualization. It uses accessible language to target a broad audience while maintaining credibility.

I then tried prompting "Analyze the communicative strategies that transform the complexity of these technical artifacts into accessible objects in the corpus"

/The corpus demonstrates several strategies for transforming the complexity of video model technologies into accessible narratives. These strategies are crucial for bridging the gap between technical audiences (developers, researchers) and general audiences (users, stakeholders). ... 
(My selection and reorganized)
. Simplification Through Narrative Framing, Metaphors and Analogies
Relating Abstract to Tangible: Complex processes like 3D modeling or video generation are explained using metaphors (e.g., "step into an image," "generating worlds"), fostering intuitive understanding.
Focus on Practical Applications: The texts emphasize real-world use cases (e.g., "movies," "games," "immersive worlds") to ground abstract concepts in familiar contexts.
Temporal Framing: Frequent use of terms like "first step," "future," and "next generation" frames advancements as part of an ongoing journey, making the technology feel progressive and approachable.Humanizing Technology: Use of personification (e.g., models “learning” or “interpreting”) to relate AI processes to human cognition.
. Selective Focus on Features
Highlighting Benefits Over Mechanics: The announcements prioritize the outcomes (e.g., “enhanced creativity,” “better user experiences”) over detailed technical explanations, reducing cognitive load.
Strategic Omission: Avoidance of jargon-heavy descriptions (e.g., deep technical terms related to neural networks) ensures accessibility. Short Sentences and Lists: The texts rely on clear and concise structures, breaking down information into digestible parts.
Headlines and Keywords: Recurrent emphasis on terms like "AI," "video," and "generation" reinforces key messages without overloading details.
. Engagement with Visual and Experiential Language
Imagistic Phrasing: Words like "explore," "view," "world," and "scene" evoke vivid imagery, creating an experiential connection between the audience and the technology.
Active Voice and Direct Address: Sentences like "You’ll explore" and "This lets you step into" involve the audience directly, fostering engagement. This includes Subjectivity in Future Projections exemplified in references to aspirational goals (e.g., "changing how we make movies") inspire excitement while leaving room for interpretation.

They are quite minimal information value on the research side aka the under the hood details. However, what stands out in this output is the document corpus' reliance on comparative strategies.

UPDATE:
I return to this project, my notebook has failed and i have to spend quite some time getting back into it, the file directory seems out of touch with my latest work.
I read the course literature and consider doing a comparative project instead, looking at how similar the documents are (cosine). But I decide to doing topic modeling for my assignment as an exploratory take on the research question. I'm setting up a new Notebook modeled on the nlp2 Notebook.

