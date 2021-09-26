FROM fedora:latest

RUN dnf update -y
RUN dnf upgrade -y

# Net tools setup
RUN dnf install net-tools nmap -y

# Git setup
RUN dnf install git -y

# Python setup
RUN dnf install python3 python3-pip python-is-python3 -y