FROM mcr.microsoft.com/devcontainers/base:ubuntu

ENV PERL_MM_USE_DEFAULT=1

RUN \
  apt-get update && \
  apt-get install -y perl texlive-latex-extra latexmk chktex

RUN \
  sudo cpan -i App::cpanminus && \
  sudo cpanm YAML::Tiny && \
  sudo cpanm File::HomeDir

RUN \
  wget https://github.com/cmhughes/latexindent.pl/releases/download/V3.21/latexindent.zip && \
  unzip -d /usr latexindent.zip && rm latexindent.zip && \
  /usr/latexindent/latexindent-module-installer.pl

ENV PATH="${PATH}:/usr/latexindent"