# Tickets-generator
Will generate you issued tickets in `.tex` format for the exam using a `.txt` file.

## Usage
1. Write a file `ticktes.txt` replacing the questions written by ChatGPT with questions from your program.
Remember that each line must be in the format: "t d question", where t denotes the topic number, d the difficulty level and question the text of the question itself.
2. run all generator cells by first changing the parameters `COMPLEXITY_GRADES`, `COMPLEXITY_MASK`, `NUMBER_OF_TICKETS`, `UNIVERSITY_NAME`, `FACULTY_NAME`, `SUBJECT_NAME` as you need. (more information in the Jupiter notebook itself)
3. The last cell will give you the text output which you should paste into `main.tex` between `\begin{document}` and `\end{document}` on the site [overleaf](https://www.overleaf).

If you did everything correctly,
your output will be a file like [this](test_gen.pdf)

I wish you success in the exam!