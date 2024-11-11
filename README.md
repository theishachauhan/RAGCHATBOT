This project develops an AI-powered chatbot designed to assist users by retrieving relevant academic information from Google Scholar. It uses a Retrieval-Augmented Generation (RAG) model that combines retrieval and generation techniques to provide in-depth answers to user queries on academic topics.

The chatbot retrieves scholarly articles' titles and abstracts, ensuring users get accurate, high-quality summaries for their research needs.

(there are two files in this code, one in which google scholar is added as the main website to retrie data from, the code is built around it so if you want to change the website, you can use the second code file (basic.ipynb) in which the wikipidea site can be interchanged with any other)

How It Works

User Query: The chatbot accepts an academic query from the user.

Question Understanding: The query is processed to extract relevant keywords using NLP techniques.

Document Retrieval: Relevant articles are retrieved from Google Scholar using the scholarly library.

Answer Generation: The RAG model generates a response based on the retrieved documents.

Display: The chatbot presents the answer to the user in a human-readable format.


License
This project is open-source and available under the MIT License.
