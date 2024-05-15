# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Simplex Generalized Linear Model Regression Function Use simplexreg With (In) R Software 
# Regression Analysis of Proportional Data Using the Simplex Distribution Use simplexreg With (In) R Software
install.packages("simplexreg")
library("simplexreg")
simplexreg = read.csv("https://raw.githubusercontent.com/timbulwidodostp/simplexreg/main/simplexreg/simplexreg.csv",sep = ";")
# Estimate Simplex Generalized Linear Model Regression Function Use simplexreg With (In) R Software
simplexreg_1 <- simplexreg(rcd~ageadj+chemo, link = "logit", data = simplexreg)
summary(simplexreg_1)
simplexreg_2 <- simplexreg(rcd~ageadj+chemo|age, link = "logit", data = simplexreg)
summary(simplexreg_2)
# Simplex Generalized Linear Model Regression Function Use simplexreg With (In) R Software 
# Regression Analysis of Proportional Data Using the Simplex Distribution Use simplexreg With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished