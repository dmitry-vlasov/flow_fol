# flow_fol
[DPLL](https://en.wikipedia.org/wiki/DPLL_algorithm) and
[first_order_resolution](https://en.wikipedia.org/wiki/Resolution_(logic))
implementation  in [flow9](https://github.com/area9innovation/flow9) language

1.  Make sure, that python, java and jre is installed on your machine

2.  Check out flow9 repository with something like

	    git clone https://github.com/area9innovation/flow9

3.  Add `flow9/bin` to your path. We also require 64-bit Java Runtime and Python in your path.

4.  Check out this repository, change directory to its root

5. Build fol_prover.jar with command:

    `build-with-flowc1 file=fol_prover.flow`

6. Run a test file with command:

    `java -jar fol_prover.jar file=dpll_test`

