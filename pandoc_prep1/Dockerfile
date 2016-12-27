################################
# Dockerfile: thedcg/pandoc-gentoo_prep1:latest

# ベース
FROM thedcg/tl-gentoo_prep8:latest

################################
# Dockerfile

# 管理者
#MAINTAINER Lemures Lemniscati <lemures.lemniscati@gmail.com>

# パッケージ
RUN date --iso-8601=ns\
 && emerge\
 dev-lang/ghc\
 app-admin/haskell-updater\
 && date --iso-8601=ns\

# 終了
