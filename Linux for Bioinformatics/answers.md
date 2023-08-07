# Answers to questions from "Linux for Bioinformatics"
Q1: What is your home directory?

A: /home/ubuntu

Q2: What is the output of this command?

A: hello_world.txt

Q3: What is the output of each ls command?

A: my_folder was empty, my_folder2 one had hello_world.txt

Q4: What is the output of each?

A: my_folder and my_folder2 was empty and myfolder3 had hello_world.txt

Q5: What editor did you use and what was the command to save your file changes?

A: nano, Ctrl+o to save and Ctrl+x to exit

Q6: What is the error?

A: Permission denied (publickey)

Q7: What was the solution?

A: Solution was to change enable password authentication in sshd_config file and restarting sshd using systemctl

Q8: what does the sudo docker run part of the command do? and what does the salmon swim part of the command do?

A: The docker run command runs a command in a new container. Swim performs a super secret operation

Q9: What is the output of this command?

A: serveruser is not in the sudoers file.  This incident will be reported.
 
Q10: What is the output of flask --version?

Python 3.10.12
Flask 2.2.2
Werkzeug 2.2.2

Q11: What is the output of mamba -V?

conda 23.1.0

Q12: What is the output of which python?

/home/serveruser/mambaforge/envs/py27/bin/python

Q13: What is the output of which python now?

/home/serveruser/mambaforge/bin/python

Q14: What is the output of salmon -h?

salmon v1.4.0 and some usage cmds and commands.

Q15: What does the -o athal.fa.gz part of the command do?

-o command writes the output to the given file name (athal.fa.gz).

Q16: What is a .gz file?

It is the gzip compressed file.

Q17: What does the zcat command do?

zcat command is used to print the contents of the compressed files in the terminal.

Q18: what does the head command do?

head command prints the top lines of the file.

Q19: what does the number 100 signify in the command?

The number 100 is used as the number of lines we want the head command to print.

Q20: What is | doing?

It's the pipe operator the output of the first command directly passes to the next command as a input.

Q21: What is a .fa file? What is this file format used for?

.fa is the fasta file. It is used to represent the sequence of nucleic acids or protein.
It has a header line which contains the information about the sequence. This line
starts with > symbol.\

Q22: What format are the downloaded sequencing reads in?

The downloaded file was in .sra file format

Q23: What is the total size of the disk?

7.6G

Q24: How much space is remaining on the disk?

1.7G

Q25: What went wrong?

The storage filled up.

Q26: What was your solution?

fastq-dump SRR074122 --gzip
