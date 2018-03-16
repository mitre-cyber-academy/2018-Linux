FROM sshd

ARG FLAG

RUN echo ${FLAG} > /etc/super_secret_flag.txt

RUN apt install -y vim
RUN chsh -s $(which vim) ctf
