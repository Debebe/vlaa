all: linreg.so 
	# Comment here preserves the prior tab
linreg.so: linreg.cpp
	"$(R_HOME)/bin/Rscript" --vanilla -e "TMB::compile('linreg.cpp','-O0 -g')"

clean:
	rm -rf *o
