# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Generalized kappa Use gkappa (ragree) With (In) R Software
install.packages("remotes")
remotes::install_github("raredd/ragree")
library("ragree")
# Estimation Generalized kappa Use gkappa (ragree) With (In) R Software
gkappa_1 = read.csv("https://raw.githubusercontent.com/timbulwidodostp/gkappa/main/gkappa/gkappa_1.csv",sep = ";")
gkappa(data = gkappa_1, id = 'patient', rater = 'rater', score = 'category')
gkappa_2 = read.csv("https://raw.githubusercontent.com/timbulwidodostp/gkappa/main/gkappa/gkappa_2.csv",sep = ";")
gkappa(ratings = gkappa_2)
# Generalized kappa Use gkappa (ragree) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished