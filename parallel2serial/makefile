.PHONY: vcs sim clean

TEST_DESIGN = parallel2serial

vcs:
		iverilog -o testResult.out ${TEST_DESIGN}.v testbench.v

sim:
		vvp -n testResult.out

clean:
		rm -rf *.log  csrc  simv*  *.key *.vpd  DVEfiles coverage *.vdb output.txt
