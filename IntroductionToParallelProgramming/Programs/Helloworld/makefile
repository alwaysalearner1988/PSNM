#define the complier
COMPILER = ifort
# compilation settings, optimization, precision, parallelization
	FLAGS = -O0 -openmp

# libraries
LIBS =  
# source list for main program
SOURCES =  helloworld.f90 
		   
test: $(SOURCES)
		${COMPILER} -o helloworld $(FLAGS) $(SOURCES)    
		
clean:
	rm *.o 

clobber:
	rm helloworld
