# MATLAB
MATLAB tutorials


str1 = punctuation
Lstr1=length(str1)

str_ch='[a-z]'
str_caps='[A-Z]'
str_nums='[0-9]'
str_space='\s'

ind_ch='regexp(str1,str_ch)'
ind_caps='regexp(str1,str_caps)'
ind_nums='regexp(str1,str_nums)'
ind_space='regexp(str1,str_space)'

mask=[ind_ch ind_caps ind_nums ind_space]
