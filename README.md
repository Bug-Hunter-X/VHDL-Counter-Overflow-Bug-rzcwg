# VHDL Counter Overflow Bug

This repository demonstrates a common error in VHDL code:  an integer counter without overflow protection. The `buggy_counter.vhd` file contains a VHDL counter that increments on each clock cycle. However, it lacks a mechanism to handle the case when the counter reaches its maximum value (15 in this example).  This can lead to unexpected behavior or simulation errors.

The `buggy_counter_solution.vhd` file provides a corrected version that addresses the overflow issue.