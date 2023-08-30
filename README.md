# The latent cognitive structures of social networks

A jupyter notebook tutorial corresponding to the work _The latent cognitive structures of social networks_ by Izabel Aguiar and Johan Ugander (2023).

The `CSS NNTuck Code Tutorial.pynb` notebook steps through the methods discussed and performs the NNTuck on the Krackhardt Advice CSS from Krackhardt (1987).

The code depends on the following packages and the version number for which it is reproducible is noted. `numpy` (`version 1.22.2`), `tensorly` (`version 0.5.1`), `sklearn` (`version 0.23.2`), `networkx` (`version 3.0`), and `matplotlib` (`version 3.3.2`). When sweeping over parameters $K$ and $C$ in the NNTuck it is most efficient to run the sweep in parallel, which depends on `joblib` (`version 1.0.1`) and on `os` to make sure the parallel runs don't use too much CPU.

Any additional tools which may not be descibed here are described in [the github page](https://github.com/izabelaguiar/NNTuck) for [_A factor model of multilayer network interdependence_ (Aguiar, Taylor, Ugander, 2022).](https://arxiv.org/abs/2206.01804)

If you use this code, please cite _The latent cognitive structures of social networks_ by Izabel Aguiar and Johan Ugander (2023) and/or [_A factor model of multilayer network interdependence_ (Aguiar, Taylor, Ugander, 2022).](https://arxiv.org/abs/2206.01804).

If you  have any questions about this code repository or the work in general, please email me at `izzya@stanford.edu`!
