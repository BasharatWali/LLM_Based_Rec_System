This repository demonstrates a medicine recommendation system that leverages ClinicalBERT and PubMedBERT from Hugging Face for embedding generation of patient and prescription data. After creating high-quality embeddings, we apply Locality-Sensitive Hashing (LSH) to efficiently compute similarity and recommend the top three medicines.

Our approach is evaluated against a SimHash-based system on two main metrics:

    Time Efficiency – How quickly top-3 recommendations are generated.
    Similarity Score – How relevant the recommended medicines are, based on embedding proximity.

Results demonstrate that leveraging these LLM-based models (ClinicalBERT & PubMedBERT) alongside LSH outperforms SimHash in both speed and accuracy, making it a promising solution for real-time, high-accuracy medical recommendation scenarios.

Features:

    Embedding generation with ClinicalBERT and PubMedBERT.
    Locality-Sensitive Hashing (LSH) for fast, approximate nearest-neighbor retrieval.
    Easy comparison of SimHash vs. LSH results on time and similarity.

Use Cases:

    Personalized medicine recommendations.
    Clinical decision support systems requiring efficient and accurate retrieval.
    Research on embedding-based retrieval methods in healthcare
