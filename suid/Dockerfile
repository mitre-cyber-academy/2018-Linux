FROM sshd

ARG FLAG

RUN echo ${FLAG} > /flag.txt
RUN chmod 000 /flag.txt

RUN chmod u+s $(which sed)
