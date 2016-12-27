################################
# Dockerfile: thedcg/pandoc-gentoo:latest

# ベース
FROM thedcg/pandoc-gentoo_prep2:latest

################################
# Dockerfile

# 管理者
#MAINTAINER Lemures Lemniscati <lemures.lemniscati@gmail.com>

# パッケージ
RUN date --iso-8601=ns\
 && emerge\
 app-text/pandoc\
 dev-haskell/pandoc-citeproc\
 dev-haskell/pandoc-types\
 && date --iso-8601=ns\

# && emerge --depclean\
# && eclean-dist --deep\
# && echo '======== equery list * ========'\
# && equery list '*'\

#RUN eclean-pkg --deep

# 終了
