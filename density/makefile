######################################
#                                    #
#        Makefile for density        #
#                                    #
######################################

flag = -O3

density.exe: main.f90
	ifort -qopenmp -parallel -ipo $(flag) $^ -o $@
