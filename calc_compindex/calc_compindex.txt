# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Calculating composite indicator automatically step by step Use calc_compindex (compindexR) With (In) R Software
install.packages("compindexR")
library("compindexR")
calc_compindex = read.csv("https://raw.githubusercontent.com/timbulwidodostp/calc_compindex/main/calc_compindex/calc_compindex.csv",sep = ";")
# Estimation Calculating composite indicator automatically step by step Use calc_compindex (compindexR) With (In) R Software
x <- calc_compindex
calc_compindex <- calc_compindex(x, avg_type = "simple", scaling_method = "min-max", vif_based_calc = FALSE, si_diff = 0.1)
calc_compindex
# Calculating composite indicator automatically step by step Use calc_compindex (compindexR) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished