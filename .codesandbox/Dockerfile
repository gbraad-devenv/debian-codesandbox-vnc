FROM debian:bullseye
 
# Install htop
RUN apt update -y \
    && apt install -y tightvncserver novnc i3 \
    && echo exec i3 > ~/.xsession
