
<p align="center">
English|<a href="README.fr.md">French</a>
</p>
# Chatbot-France Marriage Law

Create a French chatbot for answering questions based on a document using Google Colab. In our case, we use data extracted from France law website: [French Law Website](https://www.legifrance.gouv.fr/codes/section_lc/LEGITEXT000006070721/LEGISCTA000006117710/#LEGISCTA000006117710)

Dataset extracted from the website can be found in "data.csv".

Two models (based on Camembert model) are used for creating answers:

1. **Dense Passage Retrieval Model**: This model is used to efficiently retrieve relevant passages of text from the document.

2. **Question Answering Model**: This model is used for answering questions based on the retrieved passages.

Model being used for question answering: [Camembert Base SQuAD-FR](https://huggingface.co/etalab-ia/camembert-base-squadFR-fquad-piaf)
