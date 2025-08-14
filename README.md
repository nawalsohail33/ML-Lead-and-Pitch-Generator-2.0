# ML-Lead-and-Pitch-Generator-2.0
This is the second version of the project ML Leade and Pitch Generator 
This upgraded version of AdorAI Lead-n-Pitch moves beyond keyword matching by using semantic search with Sentence-BERT embeddings.
It not only finds the most relevant companies for your services but also generates personalized pitches for each company using Google Gemini.

 How It Works
Data Input

A CSV/Excel file with company names, descriptions, and other relevant details.

User Query

The user enters a description of the services they provide.

Semantic Embeddings (Sentence-BERT)

Both the company descriptions and the user query are converted into dense vector embeddings using Sentence-BERT (via sentence-transformers library).

This allows the system to understand meaning and context, not just keywords.

Similarity Matching

Cosine similarity is calculated between the query embedding and each company embedding.

The top matches are identified as the most relevant leads.

AI-Powered Pitch Generation (Gemini)

For each matched company, a customized pitch is generated using Google Gemini.

Tech Stack (v2)
Python – Core programming language.

Pandas – For data handling.

Sentence-Transformers (Sentence-BERT) – For semantic embeddings.

scikit-learn – For cosine similarity calculation.

NumPy – For vector operations.

Google Gemini API – For generating personalized pitches.
The pitch is tailored to the company’s profile, highlighting how the user’s services align with their needs.

