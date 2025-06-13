## ZoneOS update (2025-06-06)

  * PHP 8.3.22 and 8.4.8
  * ModSecurity 2.9.10 (fixes CVE 2025-47947 and CVE 2025-48866)
  * Added pgvector-0.8.0 extension for PostgreSQL.
  * Added excimer PECL module.

## ZoneOS update (2025-05-23)

  * MariaDB 11.4.7
  * Nodejs 20.19.2 (ZoneOS 23.11.00)
  * Nodejs 22.15.1 (ZoneOS 25.05.00)

## ZoneOS 25.05.00 

  * Moved to OpenSSL 3.5.0
  * Added Postgresql 17.4
  * Added Python 3.13.1
  * Perl 5.40
  * Nodejs 22.15.0
  * Moved to 6.6 LTS kernel, glibc-2.40 and gcc-13

<details>
  <summary>Detailed list of software version changes</summary>

  ### Changes
  * app-antivirus/clamav 1.0.3 -> 1.4.2
  * app-arch/brotli 1.0.9-r5 -> 1.1.0
  * app-arch/bzip2 1.0.8-r4 -> 1.0.8-r5
  * app-arch/gzip 1.12-r4 -> 1.13-r1
  * app-arch/lz4 1.9.4 -> 1.10.0-r1
  * app-arch/p7zip 16.02-r8 -> 17.05-r1
  * app-arch/pigz 2.7 -> 2.8
  * app-arch/tar 1.34-r3 -> 1.35
  * app-arch/unrar 6.2.8 -> 7.0.9
  * app-arch/xz-utils 5.4.2 -> 5.8.1
  * app-arch/zstd 1.5.5 -> 1.5.6
  * app-crypt/gnupg 2.2.41 -> 2.4.6-r1
  * app-crypt/gpgme 1.18.0-r2 -> 1.23.2-r2
  * app-crypt/libmd 1.0.4 -> 1.1.0
  * app-crypt/mit-krb5 1.20.1 -> 1.21.3
  * app-editors/nano 7.2 -> 8.2
  * app-editors/vim 9.0.1403 -> 9.1.0366
  * app-editors/vim-core 9.0.1403 -> 9.1.0366-r1
  * app-misc/ca-certificates 3.91 -> 3.107
  * app-misc/jq 1.7_pre20201109-r1 -> 1.7.1-r1
  * app-misc/mc 4.8.28-r2 -> 4.8.32-r1
  * app-misc/tmux 3.3a-r1 -> 3.5a
  * app-shells/bash 5.1_p16-r2 -> 5.2_p37
  * app-text/ghostscript-gpl 10.0.0-r5 -> 10.05.0
  * dev-db/freetds 1.2.18 -> 1.4.17
  * dev-db/mariadb-connector-c 3.4.3 -> 3.4.5
  * dev-db/redis 7.0.12 -> 7.4.1
  * dev-db/sqlite 3.42.0 -> 3.46.1
  * dev-db/unixODBC 2.3.9 -> 2.3.12
  * dev-lang/perl 5.36.0-r1 -> 5.40.0
  * dev-libs/expat 2.5.0 -> 2.6.4
  * dev-libs/fribidi 1.0.12 -> 1.0.13
  * dev-libs/icu 72.1 -> 75.1
  * dev-libs/json-c 0.16-r1 -> 0.18
  * dev-libs/libfastjson 0.99.9-r1 -> 1.2304.0
  * dev-libs/libpcre2 10.42-r1 -> 10.44-r1
  * dev-libs/librdkafka 1.8.2 -> 2.2.0-r1
  * dev-libs/libsodium 1.0.18_p20220618 -> 1.0.20
  * dev-libs/libxml2 2.10.4 -> 2.12.10
  * dev-libs/libzip 1.9.2 -> 1.11.2
  * dev-libs/oniguruma 6.9.8 -> 6.9.9
  * dev-libs/openssl 1.1.1w -> 3.5.0
  * dev-libs/protobuf 21.9 -> 28.0
  * dev-libs/protobuf-c 1.4.1 -> 1.5.0-r2
  * dev-php/blackfire 1.91.0 -> 1.92.32
  * dev-php/ioncube 13.0.2 -> 14.4.0
  * dev-php/maxminddb 1.11.0-r2 -> 1.12.0
  * dev-php/newrelic 10.14.0.3 -> 11.8.0.22
  * dev-php/pecl-mailparse 3.1.6 -> 3.1.8
  * dev-php/pecl-memcached 3.2.0-r1 -> 3.3.0
  * dev-php/pecl-mongodb 1.17.0 -> 2.0.0
  * dev-php/pecl-protobuf 3.24.2 -> 4.28.0
  * dev-php/pecl-rdkafka 6.0.3-r1 -> 6.0.5
  * dev-php/pecl-redis 5.3.7-r1 -> 6.2.0
  * dev-php/pecl-xdebug 3.2.2 -> 3.4.2
  * dev-php/sourceguardian 14.0.3 -> 16.0.2
  * dev-python/mysqlclient 2.1.1 -> 2.2.6
  * dev-python/pip 22.3.1 -> 24.3.1-r2
  * dev-python/pymongo 4.3.3 -> 4.10.1
  * dev-python/setuptools 65.6.3 -> 75.6.0-r1
  * dev-python/virtualenv 20.16.7 -> 20.28.0
  * dev-vcs/git 2.42.1 -> 2.49.0
  * gnome-base/librsvg 2.40.21 -> 2.57.3
  * mail-mta/postfix 3.6.10 -> 3.9.1
  * media-gfx/gifsicle 1.93 -> 1.95
  * media-gfx/imagemagick 7.1.1.12 -> 7.1.1.43
  * media-gfx/jpegoptim 1.4.6 -> 1.5.5
  * media-gfx/libimagequant 4.1.0 -> 4.3.0
  * media-gfx/optipng 0.7.7-r1 -> 0.7.8
  * media-gfx/pngquant 2.17.0 -> 2.18.0
  * media-gfx/wkhtmltopdf 0.12.6 -> 0.12.6.1
  * media-libs/fontconfig 2.14.2 -> 2.15.0-r1
  * media-libs/freetype 2.12.1-r2 -> 2.13.3
  * media-libs/gd 2.3.3-r3 -> 2.3.3-r4
  * media-libs/harfbuzz 6.0.0 -> 10.1.0
  * media-libs/jbig2dec 0.19 -> 0.20
  * media-libs/lcms 2.14-r4 -> 2.16-r1
  * media-libs/libaom 3.5.0 -> 3.9.1
  * media-libs/libde265 1.0.9 -> 1.0.15
  * media-libs/libepoxy 1.5.10-r1 -> 1.5.10-r3
  * media-libs/libglvnd 1.6.0 -> 1.7.0
  * media-libs/libheif 1.13.0 -> 1.18.2-r1
  * media-libs/libjpeg-turbo 2.1.4 -> 3.0.3-r1
  * media-libs/libpng 1.6.39 -> 1.6.44
  * media-libs/libwebp 1.2.4-r2 -> 1.4.0
  * media-libs/openjpeg 2.5.0-r4 -> 2.5.2
  * media-libs/tiff 4.5.0-r2 -> 4.6.0-r1
  * media-video/ffmpeg 4.4.3 -> 6.1.2
  * net-analyzer/traceroute 2.1.1 -> 2.1.5
  * net-dns/bind 9.16.44 -> 9.18.33
  * net-dns/libidn 1.41 -> 1.42
  * net-dns/libidn2 2.3.4 -> 2.3.7
  * net-libs/grpc 1.52.1 -> 1.65.1
  * net-libs/nghttp2 1.57.0 -> 1.62.1
  * net-libs/serf 1.3.9-r3 -> 1.3.10
  * net-misc/curl 8.4.0 -> 8.12.1
  * net-misc/memcached 1.6.19 -> 1.6.27
  * net-misc/openssh 9.3_p2 -> 9.9_p2
  * net-misc/rsync 3.2.4-r3 -> 3.3.0-r2
  * net-misc/wget 1.21.3-r1 -> 1.25.0
  * net-misc/whois 5.5.14 -> 5.5.23
  * net-nds/openldap 2.6.3-r7 -> 2.6.8
  * sys-apps/bat 0.21.0 -> 0.24.0-r1
  * sys-apps/coreutils 9.1-r2 -> 9.5
  * sys-apps/diffutils 3.9-r1 -> 3.10
  * sys-apps/file 5.44-r3 -> 5.45-r4
  * sys-apps/findutils 4.9.0-r2 -> 4.10.0
  * sys-apps/gawk 5.2.1 -> 5.3.1
  * sys-apps/grep 3.8-r1 -> 3.11-r1
  * sys-apps/less 608-r2 -> 668
  * sys-apps/util-linux 2.38.1 -> 2.40.2
  * sys-devel/gettext 0.21.1 -> 0.22.5
  * sys-kernel/zoneos-kernel 5.15.138 -> 6.6.89
  * sys-libs/glibc 2.36-r5 -> 2.40-r5
  * sys-libs/timezone-data 2022g -> 2024a-r1
  * sys-libs/zlib 1.2.13-r1 -> 1.3.1-r1
  * sys-process/htop 3.2.2 -> 3.3.0
  * www-apache/mod_security 2.9.7 -> 2.9.8
  * www-servers/apache 2.4.58 -> 2.4.62
  * www-servers/nginx 1.24.0-r1 -> 1.26.3
</details>

## ZoneOS 23.11.00 update (2025-05-09)

  * PHP versions 8.3.21 and 8.4.7
  * MariaDB versions 10.6.22 and 11.4.6
  * MySQL versions 8.0.42 and 8.4.5
  * LibXML2 version 2.12.10

## ZoneOS 23.11.00 update (2025-04-07)

  * PHP versions 8.3.20 and 8.4.6

## ZoneOS 23.11.00 update (2025-03-14)

  * PHP versions 8.1.32, 8.2.28, 8.3.19 and 8.4.5
  * Freetype 2.13.3

## ZoneOS 23.11.00 update (2025-02-13)

  * PHP versions 8.3.17 and 8.4.4
  * MariaDB versions 10.6.21 and 11.4.5
  * OpenSSH 9.9p2

## ZoneOS 23.11.00 update (2025-01-23)

  * PHP versions 8.3.16 and 8.4.3
  * MySQL versions 8.0.41 and 8.4.4
  * Rsync 3.3.0
  * Git 2.42.4
  * Nodejs 20.18.2

