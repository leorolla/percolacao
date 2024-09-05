
for a in *.tex ; do pdflatex --jobname=${a%.*} "\def\filename{$a} \input{master/master.tex}" ; done

