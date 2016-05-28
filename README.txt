CYK ALGORITHM V.1.0 (PYTHON)
-----------------------------
Creator: Juan Pablo Arevalo

How To Use:

1) Create a txt file and write down your grammar in CNF (Chomsky Normal Form)
2) Create a txt file with the words you want to analize
3.1) If the files are named "gramatica.txt" and "palabras.txt"
	3.1.1) Run tarea2.py (There's a "main" that will accept those filenames)
3.2) If the files have different names
	3.2.1) Edit tarea2.py and update the filenames to their respective values on line 170
	3.2.2) Run tarea2.py
4) Enjoy!


RULES:

GRAMMAR:
	i) The first line must contain the number of RULES present in the grammar.
	ii) The grammar MUST BE written in CHOMSKY NORMAL FORM (CNF).
	iii) The format for each rule can be either A -> BC or A->BC.
	iv) Each RULE must be in a different line.
	v) In case of multiple products for a same state, re-write so you have a single state->product for each line.
	vi) The first RULE is represented by the INITIAL STATE followed by one of its products.
	vii) Write down only ONE grammar per file.

WORDS:	
	i) The first line must contain the number of RULES present in the grammar.
	ii) Each WORD must be in a different line.


For further help, feel free to check out the given files in order to understand the input rules and format.

