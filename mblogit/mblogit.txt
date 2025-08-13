# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Baseline-Category Logit Models for Categorical and Multinomial Responses Use mblogit (mclogit) With (In) R Software
install.packages("mclogit")
library("mclogit")
library("MASS")
library("nnet")
library("memisc")
mblogit = read.csv("https://raw.githubusercontent.com/timbulwidodostp/mblogit/main/mblogit/mblogit.csv",sep = ";")
# Estimation Baseline-Category Logit Models for Categorical and Multinomial Responses Use mblogit (mclogit) With (In) R Software
mblogit <- mblogit(factor(c(mblogit)) ~ mblogit_1 + mblogit_2 + mblogit_3, weights = mblogit_4, data = mblogit)
summary(mblogit)
mtable(mblogit)
# Baseline-Category Logit Models for Categorical and Multinomial Responses Use mblogit (mclogit) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished