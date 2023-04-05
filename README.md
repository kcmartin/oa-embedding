# oa-embedding
Project 8 for OpenAI-PythonAPI course - Text Embedding

This is Project 8 for the OpenAI-PythonAPI course - Text Embedding as a more cost-effective alternative to fine-tuning

Notes: 

Got the following numpy error, due to the a problem with the data file.

```  File "<__array_function__ internals>", line 200, in dot
numpy.core._exceptions._UFuncNoLoopError: ufunc 'multiply' did not contain a loop with signature matching types (dtype('<U34391'), dtype('<U32')) -> None```

A fellow student suggested a fix in the course forum using `ast`
