## ZoneOS update (2026-06-05)

- MariaDB 10.6.27, 11.4.12 and 11.8.8
- PHP 8.4.22 and 8.5.7
- Python 3.11.15 and 3.13.13 (Fixes CVE-2026-24515, CVE-2026-25210, CVE-2025-59375)
- Nodejs 24.16.0
- PostgreSQL 14.23 and 17.10 (Fixes many CVEs - https://www.postgresql.org/docs/17/release-17-10.html)
- Redis 8.2.6 (Fixes CVE-2026-23479, CVE-2026-23631, CVE-2026-25243, CVE-2026-25588, CVE-2026-25589)
- Blackfire 2026.5.0
- Newrelic 12.7.0.36
- PECL brotli 0.19.0
- PECL mongodb 2.3.3
- Bind 9.20.23 (Fixes CVE-2026-3593, CVE-2026-5947, CVE-2026-5950, CVE-2026-5946, CVE-2026-3039, CVE-2026-3592)
- Gnutls 3.8.13 (Fixes many CVEs - https://gnutls.org/security-new.html)
- Memcached 1.6.42
- Rsync 3.4.3 (Fixes many CVEs - https://download.samba.org/pub/rsync/NEWS#3.4.3)
- Imagemagick 7.1.2.25

## ZoneOS update (2026-05-11)

- MySQL 8.0.46 and 8.4.9
- PHP 8.2.31, 8.3.31, 8.4.21 and 8.5.6

## ZoneOS 26.05.00

  * Moved to newer core – glibc-2.42, gcc-14 etc
  * Updates all over.

<details>
  <summary>Detailed list of software version changes</summary>
  * app-accessibility/at-spi2-core 2.52.0 -> 2.56.5
  * app-admin/rsyslog 8.2404.0-r3 -> 8.2602.0
  * app-antivirus/clamav 1.4.3 -> 1.5.2
  * app-arch/gzip 1.13-r1 -> 1.14
  * app-arch/lbzip2 2.5_p20181227-r2 -> 2.5_p20181227-r3
  * app-arch/libarchive 3.7.9 -> 3.8.6
  * app-arch/p7zip 17.05-r1 -> 17.05-r2
  * app-arch/snappy 1.1.10-r1 -> 1.2.2-r1
  * app-arch/unrar 7.0.9 -> 7.2.4
  * app-arch/unzip 6.0_p27-r1 -> 6.0_p29
  * app-arch/xz-utils 5.8.1 -> 5.8.2
  * app-arch/zstd 1.5.6 -> 1.5.7-r1
  * app-crypt/gnupg 2.4.9 -> 2.5.17-r2
  * app-crypt/gpgme 1.23.2-r2 -> 2.0.1-r1
  * app-crypt/mit-krb5 1.21.3 -> 1.21.3-r1
  * app-crypt/pinentry 1.3.1 -> 1.3.2-r1
  * app-editors/nano 8.2 -> 8.7.1
  * app-misc/ca-certificates 3.118.1 -> 3.123
  * app-misc/jq 1.7.1-r1 -> 1.8.1
  * app-misc/mc 4.8.32-r1 -> 4.8.33
  * app-shells/bash 5.2_p37 -> 5.3_p9
  * app-text/aspell 0.60.8.1-r1 -> 0.60.8.2
  * app-text/enchant 2.6.1 -> 2.8.12
  * app-text/ghostscript-gpl 10.05.1 -> 10.06.0
  * dev-db/freetds 1.4.17 -> 1.5
  * dev-db/mariadb-connector-c 3.4.5 -> 3.4.7
  * dev-db/postgresql 17.7 -> 17.9
  * dev-db/sqlite 3.46.1 -> 3.51.2
  * dev-db/unixODBC 2.3.12 -> 2.3.12-r2
  * dev-debug/strace 6.9 -> 6.19
  * dev-lang/lua 5.4.6 -> 5.4.8
  * dev-lang/luajit 2.1.1716656478-r1 -> 2.1.1731601260
  * dev-lang/orc 0.4.40-r1 -> 0.4.41
  * dev-lang/perl 5.40.0 -> 5.42.0-r1
  * dev-libs/expat 2.6.4 -> 2.8.0
  * dev-libs/fribidi 1.0.13 -> 1.0.16
  * dev-libs/glib 2.80.5-r1 -> 2.84.4
  * dev-libs/hiredis 1.2.0 -> 1.3.0
  * dev-libs/icu 75.1 -> 78.2
  * dev-libs/jansson 2.14-r2 -> 2.14.1
  * dev-libs/libaio 0.3.113-r1 -> 0.3.113_p8
  * dev-libs/libassuan 3.0.0 -> 3.0.0-r1
  * dev-libs/libfastjson 1.2304.0 -> 1.2304.0-r1
  * dev-libs/libffi 3.4.6 -> 3.5.2
  * dev-libs/libfmt 9.1.0-r2 -> 12.1.0
  * dev-libs/libgcrypt 1.11.0-r1 -> 1.12.1
  * dev-libs/libgit2 1.8.4 -> 1.9.2
  * dev-libs/libgpg-error 1.50 -> 1.59
  * dev-libs/libksba 1.6.7 -> 1.6.8
  * dev-libs/libltdl 2.4.7-r1 -> 2.5.4
  * dev-libs/libmaxminddb 1.11.0 -> 1.12.2
  * dev-libs/libnl 3.10.0 -> 3.12.0
  * dev-libs/libpcre 8.45-r3 -> 8.45-r4
  * dev-libs/libpcre2 10.44-r1 -> 10.47
  * dev-libs/librdkafka 2.2.0-r1 -> 2.10.0
  * dev-libs/libsodium 1.0.20 -> 1.0.21_p20260122
  * dev-libs/libtasn1 4.19.0 -> 4.21.0
  * dev-libs/libunistring 1.2 -> 1.3
  * dev-libs/libuv 1.49.2 -> 1.51.0-r1
  * dev-libs/libxml2 2.12.10 -> 2.15.2-r1
  * dev-libs/libxslt 1.1.39-r1 -> 1.1.45
  * dev-libs/libzip 1.11.2 -> 1.11.4-r2
  * dev-libs/mpdecimal 4.0.0 -> 4.0.1
  * dev-libs/nettle 3.10 -> 3.10.2
  * dev-libs/npth 1.7-r1 -> 1.8
  * dev-libs/nspr 4.36 -> 4.38.2
  * dev-libs/nss 3.101.2 -> 3.112.5
  * dev-libs/oniguruma 6.9.9 -> 6.9.10
  * dev-libs/openssl 3.5.5 -> 3.5.6
  * dev-libs/protobuf 28.0 -> 31.1
  * dev-libs/protobuf-c 1.5.0-r2 -> 1.5.2
  * dev-libs/simdjson 3.11.0 -> 4.3.0
  * dev-libs/snowball-stemmer 2.2.0 -> 3.0.1
  * dev-libs/userspace-rcu 0.14.1 -> 0.15.6
  * dev-libs/xxhash 0.8.2 -> 0.8.3
  * dev-perl/DBI 1.645.0 -> 1.647.0
  * dev-python/mysqlclient 2.2.6 -> 2.2.8
  * dev-python/pip 24.3.1-r2 -> 26.0.1
  * dev-python/requests 2.32.3 -> 2.33.1
  * dev-python/setuptools 75.6.0-r1 -> 81.0.0
  * dev-python/urllib3 2.2.3 -> 2.6.3
  * dev-python/virtualenv 20.28.0 -> 20.39.1
  * dev-vcs/git 2.49.1 -> 2.53.0
  * dev-vcs/subversion 1.14.2-r1 -> 1.14.5-r2
  * gnome-base/librsvg 2.57.3 -> 2.60.0
  * mail-mta/postfix 3.9.1 -> 3.10.9
  * media-gfx/gifsicle 1.95 -> 1.96
  * media-gfx/imagemagick 7.1.2.17 -> 7.1.2.21
  * media-gfx/jpegoptim 1.5.5 -> 1.5.6
  * media-gfx/libimagequant 4.3.0 -> 4.3.4
  * media-libs/dav1d 1.4.2 -> 1.5.0
  * media-libs/fontconfig 2.15.0-r1 -> 2.17.1
  * media-libs/freetype 2.13.3 -> 2.14.3
  * media-libs/harfbuzz 10.1.0 -> 12.3.2
  * media-libs/lcms 2.16-r1 -> 2.17
  * media-libs/libaom 3.9.1 -> 3.12.1
  * media-libs/libavif 1.1.1 -> 1.3.0
  * media-libs/libde265 1.0.15 -> 1.0.16
  * media-libs/libheif 1.18.2-r1 -> 1.20.2
  * media-libs/libjpeg-turbo 3.0.3-r1 -> 3.1.3
  * media-libs/libogg 1.3.5-r1 -> 1.3.6
  * media-libs/libvorbis 1.3.7-r1 -> 1.3.7-r2
  * media-libs/libwebp 1.4.0 -> 1.6.0
  * media-libs/openjpeg 2.5.2 -> 2.5.3-r1
  * media-libs/tiff 4.6.0-r1 -> 4.7.1
  * media-libs/x265 3.6-r1 -> 4.1
  * media-video/ffmpeg 6.1.2 -> 8.1
  * net-dns/bind 9.18.47 -> 9.20.22
  * net-dns/libidn 1.42 -> 1.43
  * net-dns/libidn2 2.3.7 -> 2.3.8
  * net-ftp/lftp 4.9.2-r1 -> 4.9.3
  * net-libs/grpc 1.65.1 -> 1.71.0
  * net-misc/curl 8.19.0 -> 8.20.0
  * net-misc/ipcalc 0.42_p2 -> 0.51-r1
  * net-misc/iputils 20240905 -> 20250605-r3
  * net-misc/memcached 1.6.27 -> 1.6.39
  * net-misc/openrdap 0.9.0_p20191017-r1 -> 0.9.1
  * net-misc/openssh 10.2_p1 -> 10.3_p1
  * net-misc/whois 5.5.23 -> 5.6.6
  * sys-apps/bat 0.24.0-r1 -> 0.25.0-r1
  * sys-apps/coreutils 9.5 -> 9.10
  * sys-apps/diffutils 3.10 -> 3.12
  * sys-apps/file 5.45-r4 -> 5.47-r1
  * sys-apps/gawk 5.3.1 -> 5.3.2
  * sys-apps/grep 3.11-r1 -> 3.12
  * sys-apps/less 668 -> 692
  * sys-apps/ripgrep 14.1.1-r1 -> 15.1.0
  * sys-apps/systemd 255.22 -> 257.10-r1
  * sys-apps/util-linux 2.40.2 -> 2.41.3-r1
  * sys-apps/which 2.21 -> 2.23
  * sys-devel/bc 1.07.1-r6 -> 1.08.2
  * sys-devel/patch 2.7.6-r4 -> 2.8-r1
  * sys-kernel/zoneos-kernel 6.6.133 -> 6.18.32
  * sys-libs/cracklib 2.10.2 -> 2.10.3
  * sys-libs/db 5.3.28-r10 -> 5.3.28-r11
  * sys-libs/gdbm 1.24 -> 1.26
  * sys-libs/glibc 2.40-r5 -> 2.42-r5
  * sys-libs/ncurses 6.4_p20240414 -> 6.5_p20251220
  * sys-libs/openipmi 2.0.36 -> 2.0.37
  * sys-libs/readline 8.2_p13-r1 -> 8.3_p3
  * sys-libs/slang 2.3.3-r1 -> 2.3.3-r2
  * sys-libs/timezone-data 2024a-r1 -> 2026a
  * sys-libs/zlib 1.3.1-r1 -> 1.3.2-r1
  * sys-process/htop 3.3.0 -> 3.4.1-r2
  * www-apache/mod_security 2.9.12 -> 2.9.13
  * www-servers/apache 2.4.66-r1 -> 2.4.67
  * x11-libs/cairo 1.18.2-r1 -> 1.18.4-r1
  * x11-libs/gtk+ 3.24.48 -> 3.24.51
  * x11-libs/pango 1.52.2 -> 1.57.0
  * x11-libs/pixman 0.44.2 -> 0.46.4
</details>

## ZoneOS update (2026-04-13)

- PHP 8.4.20 and 8.5.5
- Libpng 1.6.57 (Fixes CVE-2026-33416, CVE-2026-34757)
- OpenSSL 3.5.6 (Fixes many CVE-s - https://openssl-library.org/news/vulnerabilities/)
- OpenSSH 10.3_p1

## ZoneOS update (2026-03-26)

- PHP 8.4.19 and 8.4.9
- Python 3.11.15 and 3.13.12
- Nodejs 24.14.1 (Fixes CVE-2026-21637, CVE-2026-21710, CVE-2026-21712, CVE-2026-21713, CVE-2026-21714, CVE-2026-21715, CVE-2026-21716, CVE-2026-21717)
- Imagemagick 7.1.2-17 (Fixes many CVE-s)
- Libpng 1.6.56 (Fixes CVE-2026-33416, CVE-2026-33636)
- Bind 9.18.47 (Fixes CVE-2026-1519, CVE-2026-3104, CVE-2026-3119, CVE-2026-3591)
- Curl 8.19.0 (Fixes CVE-2026-3805, CVE-2026-3784, CVE-2026-3783, CVE-2026-1965)
- OpenSSH 10.2_p1 (Fixes CVE-2025-61984, CVE-2025-61985)

## ZoneOS update (2026-02-13)

- MariaDB 10.6.25, 11.4.10 and 11.8.6
- MySQL 8.0.45 and 8.4.8
- PHP 8.4.18 and 8.5.3
- Blackfire 1.92.60
- Newrelic 12.5.0.30
- PECL Mongodb 2.1.8
- NodeJS 24.13.1
- Libpng 1.6.55 (Fixes CVE-2026-25646)
- Rsync 3.4.1

## ZoneOS update (2026-01-30)

- Vim 9.1.1652 (Fixes CVE-2025-53905, CVE-2025-53906)
- OpenSSL 3.5.5 (Fixes many CVE-s - https://openssl-library.org/news/vulnerabilities/)
- ModSecurity 2.9.12 (Fixes CVE-2025-54571)
- Added Ripgrep 14.1.1

## ZoneOS update (2026-01-16)

- Nodejs 24.13.0 (Fixes CVE-2025-59465, CVE-2025-55132, CVE-2025-55130, CVE-2025-59466, CVE-2025-55131, CVE-2026-21637)
- Curl 8.18.0 (Fixes CVE-2025-14017, CVE-2025-14524, CVE-2025-14819, CVE-2025-15079, CVE-2025-15224)
- Libpng 1.6.54 (Fixes CVE-2026-22695, CVE-2026-22801)
- Gnupg 2.4.9 (Fixes CVE-2025-68973)
- PHP 8.3.30, 8.4.17 and 8.5.2
- PECL Maxmind 1.13.1
- PECL Apcu 5.1.28
- PECL Brotli 0.18.3
- PECL Imagemagick 3.8.1
- PECL Xdebug 3.5.0
- Blackfire 1.92.58
- Newrelic 12.3.0.28
- Sourceguardian 17.0.0
- Imagemagick 7.1.2-12
