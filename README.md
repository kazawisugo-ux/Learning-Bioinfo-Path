# Learning-Bioinfo-Path
#台大生物機電系，研究細胞部分重編程的學習軌跡
#目標:研究山中因子(OSKM)對皮膚細胞重編程的影響，並以此申請UC Berkeley Bioe 

factors = [0.2 , 0.5, 0.6 , 0.8] #代表 Oct4 , Sox2 ,klf4 , c-Myc
average_activity = sum(factors) / len(factors)

if average_activity > 0.4 :
        print("succees")

else : 
        print("fail")
