FROM sshd

ARG FLAG


COPY super_secret_flag.txt ./etc/super_secret_flag.txt

RUN apt install -y vim
RUN chsh -s $(which vim) ctf
