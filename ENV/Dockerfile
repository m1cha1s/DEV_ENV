FROM fedora:latest

RUN dnf update -y
RUN dnf upgrade -y
RUN dnf install net-tools git python3 python3-pip python-is-python3 openssh-server -y

RUN systemctl enable sshd