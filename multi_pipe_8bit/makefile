.PHONY: vcs sim clean

TEST_DESIGN = multi_pipe_8bit

vcs:
		iverilog -o testResult.out ${TEST_DESIGN}.v testbench.v

sim:
		vvp -n testResult.out

clean:
		rm -rf testResult.out output.txt
