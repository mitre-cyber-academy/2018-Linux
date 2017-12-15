FROM sshd

ARG FLAG

RUN echo ${FLAG} > /flag.txt
RUN chmod 000 /flag.txt

RUN apt update && apt install -y vim-tiny sudo

RUN usermod -a -G sudo ctf

RUN echo ctf:tomatosoup | chpasswd

RUN touch /home/ctf/.sudo_as_admin_successful

COPY history /home/ctf/.bash_history

RUN chown -R ctf:ctf /home/ctf
