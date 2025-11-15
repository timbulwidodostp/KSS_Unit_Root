# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Kapetanios, Shin and Snell(2003) nonlinear unit root test function Use KSS_Unit_Root (NonlinearTSA) With (In) R Software
install.packages("NonlinearTSA")
library("NonlinearTSA")
KSS_Unit_Root = read.csv("https://raw.githubusercontent.com/timbulwidodostp/KSS_Unit_Root/main/KSS_Unit_Root/KSS_Unit_Root.csv",sep = ";")
# Estimation Kapetanios, Shin and Snell(2003) nonlinear unit root test function Use KSS_Unit_Root (NonlinearTSA) With (In) R Software
KSS_Unit_Root <- KSS_Unit_Root$KSS_Unit_Root
KSS_Unit_Root <-  KSS_Unit_Root(KSS_Unit_Root, case = 1, lags = 20,lsm = 3)
KSS_Unit_Root
# Kapetanios, Shin and Snell(2003) nonlinear unit root test function Use KSS_Unit_Root (NonlinearTSA) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished