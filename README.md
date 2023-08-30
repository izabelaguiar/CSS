# The latent cognitive structures of social networks

A jupyter notebook tutorial corresponding to the work `The latent cognitive structures of social networks.' Izabel Aguiar and Johan Ugander (2023)

The `CSS NNTuck Code Tutorial.pynb` notebook steps through the methods discussed and performs the NNTuck on the Krackhardt Advice CSS from Krackhardt (1987).

The code depends on the following packages and the version number for which it is reproducible is noted. `numpy` (`version 1.22.2`), `tensorly` (`version 0.5.1`), `sklearn` (`version 0.23.2`), `networkx` (`version 3.0`), and `matplotlib` (`version 3.3.2`). When sweeping over parameters $K$ and $C$ in NNTuck it is most efficient to run the sweep in parallel, which depends on `joblib` (`version 1.0.1`) and on `os` to make sure the parallel runs don't use too much CPU.

Note that the implementation of the multiplicative updates for NNTuck was done by updating the current tensorly implementation for nonnegative Tucker decomposition (which minimizes Frobenius loss instead of KL).
