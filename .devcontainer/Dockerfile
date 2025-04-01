# Use the latest Arch Linux base image
FROM archlinux:latest

# Update system and install base-devel group
RUN pacman -Syu --noconfirm base-devel

# Install other necessary packages
RUN pacman -S --noconfirm git vim python

# Any other setup steps
RUN pacman -Syu --noconfirm \
    && pacman -S --noconfirm \
    gcc \
    gdb \
    cmake \
    make \
    clang \
    boost \
    libstdc++ \
    valgrind \
    doxygen \
    ninja \
    && pacman -Scc --noconfirm 