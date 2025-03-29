.PHONY: vcs sim clean

TEST_DESIGN = radix2_div

vcs:
		iverilog -o testResult.out ${TEST_DESIGN}.v testbench.v

sim:
		vvp -n testResult.out

clean:
		rm -rf *.log  csrc  simv*  *.key *.vpd  DVEfiles coverage *.vdb output.txt
