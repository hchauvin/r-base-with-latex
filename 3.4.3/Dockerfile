FROM r-base:3.4.3

RUN apt-get update && \
  apt-get install -y texlive-base
RUN apt-get update && \
  apt-get install -y texlive-latex-base
# xzdec is used by tlmgr (texlive package manager)
RUN apt-get install -y xzdec
RUN tlmgr init-usertree && tlmgr install booktabs makecell threeparttable geometry multirow framed pgf ms xcolor