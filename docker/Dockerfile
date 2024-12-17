FROM ubuntu:22.04

WORKDIR /app

CMD apt-get update && apt-get install -y --install-recommends  \
  build-essential  \
  ccache  \
  perl  \
  python3 \
  binutils  \
  util-linux  \
  patch  \
  diffutils  \
  flex  \
  findutils  \
  grep  \
  gawk  \
  intltool  \
  gettext  \
  bzip2  \
  xz-utils  \
  unzip  \
  libncurses5-dev  \
  zlib1g-dev  \
  libssl-dev  \
  git  \
  rsync  \
  wget  \
  curl  \
  subversion  \
  time \
  python3-distutils \
  && apt-get install -y --no-install-recommends \
  software-properties-common \
  wget \
  build-essential \
  libssl-dev \
  zlib1g-dev \
  libbz2-dev \
  libreadline-dev \
  libsqlite3-dev \
  curl \
  libffi-dev \
  && rm -rf /var/lib/apt/lists/* \
  && add-apt-repository universe \
  && apt-get install -y --no-install-recommends python2 \
  && ln -s /usr/bin/python2 /usr/bin/python \
  && useradd -m -s /bin/bash cadore \ 
  && echo 'cadore:cadorepass' | chpasswd \
  && umask 022 \
#   && cd openwrt-openwrt \
#   && echo "src-git simetbox https://github.com/simetnicbr/simetbox-openwrt-feed.git" > feeds.conf
#   && cat feeds.conf.default >> feeds.conf
    && ./scripts/feeds update -a \
    && ./scripts/feeds install -a \





    1  apt-get update 
    2  apt-get install --install-recommends    build-essential    ccache    perl    python3   binutils    util-linux    patch    diffutils    flex    findutils    grep    gawk    intltool    gettext    bzip2    xz-utils    unzip    libncurses5-dev    zlib1g-dev    libssl-dev    git    rsync    wget    curl    subversion    time 
    3  apt-get update && apt-get install -y --no-install-recommends     software-properties-common     wget     build-essential     libssl-dev     zlib1g-dev     libbz2-dev     libreadline-dev     libsqlite3-dev     curl     libffi-dev     && rm -rf /var/lib/apt/lists/*
    4  add-apt-repository universe &&     apt-get update &&     apt-get install -y --no-install-recommends python2
    5  ls- l
    6  python
    7  python2
    8  ]
    9  python3
   10  ./scripts/feeds update -a
   11  ls -l
   12  cd app/openwrt/openwrt-openwrt/
   13  ./scripts/feeds update -a
   14  apt-get install  python3-distutils
   15  history
   16  ./scripts/feeds update -a
   17  ./scripts/feeds install -a
   18  make menuconfig
   19  HTOP
   20  htop
   21  make -j12
   22  make -j12 -V=s
   23  make -j12 V=s
   24  make clean
   25  make -j12 V=s
   26  adduser cadore
   27  su cadore
   28  ls -l
   29  cd ..
   30  ls -l
   31  cd ..
   32  ls -l
   33  cd openwrt/openwrt-openwrt/
   34  ls -l
   35  cd ..
   36  ls -
   37  lls -l
   38  ls -l
   39  cd openwrt-openwrt/
   40  ls -l
   41  chown -R cadore:cadore ./*  
   42  ls -l
   43  su cadore
   44  ls -l
   45  history