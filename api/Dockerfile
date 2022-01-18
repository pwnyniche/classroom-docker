# Tải node version 16
FROM node:16
# Quy định port 7000
ENV PORT 7000

# Tạo thư mục chứa source code


# Tạo User mới có tên là classroomapi
ARG user=classroomapi
ARG UID=1733
RUN useradd -m $user
RUN usermod -u $UID $user
RUN groupmod -g $UID $user
RUN printf "1\n1\n"|passwd $user
ENV HOME /home/$user
RUN usermod -aG sudo $user

# Tạo thư mục làm việc
WORKDIR /home/$user
USER $user
RUN mkdir -p /home/$user/app
WORKDIR /home/$user/app
