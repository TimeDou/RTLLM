.PHONY: vcs sim clean

TEST_DESIGN = fsm

vcs:
		iverilog -o testResult.out ${TEST_DESIGN}.v testbench.v

sim:
		vvp -n testResult.out

clean:
		rm -rf testResult.out output.txt
