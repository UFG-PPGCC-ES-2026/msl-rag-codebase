# Scopus

- Acesse https://www.scopus.com/ e logue (deve-se usar uma conta vinculada a uma instituição credenciada para liberar acesso a busca avançada: https://www.scopus.com/pages/search/publications?type=advanced).

- Cole a string no campo da query:
```
TITLE-ABS-KEY ( "Retrieval-Augmented Generation" OR "RAG" ) 
AND TITLE-ABS-KEY ( "source code" OR "codebase" OR "code repository" ) 
AND TITLE-ABS-KEY ( "LLM" OR "Large Language Model" OR "GenAI" OR "Generative AI" ) 
AND ( LIMIT-TO ( SUBJAREA , "COMP" ) ) 
AND ( LIMIT-TO ( DOCTYPE , "cp" ) OR LIMIT-TO ( DOCTYPE , "ar" ) ) 
AND ( LIMIT-TO ( LANGUAGE , "English" ) ) 
AND ( LIMIT-TO ( SRCTYPE , "p" ) OR LIMIT-TO ( SRCTYPE , "j" ) ) 
AND PUBYEAR > 2019 AND PUBYEAR < 2027
```

- Exporte os resultados em CSV ou BibTeX.