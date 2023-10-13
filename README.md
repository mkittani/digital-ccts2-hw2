verilog source code for a digital circuits hw that counts the number of bit transitions, if 1 and 0 are neighbors then we count one step. included the design and testbench to be run on eda playground


the code is perfectly running and runs all the needed cases and calculates every single transition count perfectly, but it has a single flaw in which it displays each sentence twice. the first sentence is the wrong one but the second sentence of each testcase is right one. Eg:

Data = 1111101010,(1002) , Count =  4	<---- wrong ans
Data = 1111101010,(1002) , Count =  5	<---- right  ans

Data = 1101101010,( 874) , Count =  6	<---- wrong ans
Data = 1101101010,( 874) , Count =  7	<---- right ans

