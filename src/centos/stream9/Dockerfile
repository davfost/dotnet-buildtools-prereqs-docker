FROM quay.io/centos/centos:stream9-development

# Install dependencies

RUN dnf install --setopt tsflags=nodocs --refresh -y \
        dnf-plugins-core \
    && \
    dnf config-manager --set-enabled crb \
    && \
    dnf install --setopt tsflags=nodocs -y \
        "perl(Time::HiRes)" \
        autoconf \
        automake \
        clang \
        cmake \
        curl-devel \
        doxygen \
        elfutils \
        file \
        findutils \
        gcc \
        gdb \
        git \
        glibc-langpack-en \
        hostname \
        jq \
        krb5-devel \
        libcurl-devel \
        libedit-devel \
        libicu-devel \
        libidn2-devel \
        libnghttp2-devel \
        libtool \
        libuuid-devel \
        libxml2-devel \
        lld \
        lldb-devel \
        llvm \
        lttng-ust-devel \
        lzma \
        make \
        ncurses-devel \
        numactl-devel \
        openssl-devel \
        procps-ng \
        python3 \
        python3-devel \
        readline-devel \
        sudo \
        swig \
        tar \
        wget \
        which \
        xz \
        zlib-devel \
    && \
    dnf clean all
