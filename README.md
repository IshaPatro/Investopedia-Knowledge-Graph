![Bond](https://github.com/IshaPatro/Investopedia-Knowledge-Graph/assets/44529324/f8daf511-4c94-48a8-9f91-5d99db9150af)# Building Knowledge Graphs from Investopedia

### Data Collection:
The project started with extracting detailed financial concepts and definitions from Investopedia, utilizing Python scripts with the BeautifulSoup and requests libraries. This targeted approach ensured the collection of relevant and comprehensive financial terminologies, essential for the subsequent steps.

### Data Processing:
Following the data collection, the information underwent thorough cleansing and preparation using Python's Pandas library. This step involved standardizing terms, eliminating duplicates, and resolving discrepancies to ensure the data was accurately structured for effective graph construction.

### Knowledge Graph Construction:
Advanced AI techniques from Hugging Face's transformers library were employed to construct the knowledge graph. Using the zero-shot-classification pipeline with the facebook/bart-large-mnli model, I evaluated the contextual relevance of definitions to their terms. Additionally, the question-answering pipeline with the distilbert-base-cased-distilled-squad model was used to define relationships between financial terms, effectively populating the knowledge graph with meaningful connections.

### Data Visualization:
NetworkX was used to visualize the knowledge graph, providing a graphical representation of the interconnected relationships among financial terms. This visualization aided in the intuitive exploration and analysis of the network, enhancing the understanding of how different concepts interrelate.

### Integration into Obsidian:
To make the knowledge graph interactively usable and enhance its practicality, I integrated the entire graph into Obsidian, a note-taking vault. This integration allows for dynamic exploration of the graph, where users can navigate through nodes and connections seamlessly. Storing the graph in Obsidian not only facilitated a more effective utilization of the data but also enriched the user experience, enabling real-time interaction with the graph’s content.

![Bond](https://github.com/IshaPatro/Investopedia-Knowledge-Graph/assets/44529324/b0d06bff-7ee0-418d-81c6-ca561498d325)


![Coupon](https://github.com/IshaPatro/Investopedia-Knowledge-Graph/assets/44529324/4cc08169-7a48-49be-8035-899d66e92484)


![Equities](https://github.com/IshaPatro/Investopedia-Knowledge-Graph/assets/44529324/a81b22f8-32e7-4adc-a5c2-7dd680686a15)


![Uploading Mortgage.png…]()






