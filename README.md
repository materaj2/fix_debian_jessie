# fix_debian_jessie
Fix Debian Jessie update issue

# Custom Dockerfile
#### Fix Debian Jessie Issue
RUN echo "deb http://archive.debian.org/debian/ jessie main" > /etc/apt/sources.list

RUN echo "deb-src http://archive.debian.org/debian/ jessie main" >> /etc/apt/sources.list

RUN echo "deb http://archive.debian.org/debian-security jessie/updates main" >> /etc/apt/sources.list

RUN echo "deb-src http://archive.debian.org/debian/ jessie main" >> /etc/apt/sources.list
