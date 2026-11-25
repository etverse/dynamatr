# dynamatr roadmap

dynamatr will estimate causal effects of time-varying treatments: iterated conditional expectation (ICE) g-computation, natural-history modified treatment policies, longitudinal IPW, AIPW and structural nested models, conversion to person-period data, and censoring weights for longitudinal data. Its first code is causatr's longitudinal code, moved here when causatr is brought into line with the [etverse design](https://etverse.github.io/design.html), which fixes its scope and interface. Each item's status is in the [issues](https://github.com/etverse/dynamatr/issues), not in this file.

## Work carried over from causatr

- Longitudinal AIPW with transport ([#1](https://github.com/etverse/dynamatr/issues/1)).
- Categorical outcomes for longitudinal ICE, IPW and AIPW ([#2](https://github.com/etverse/dynamatr/issues/2)).
- Stochastic interventions under longitudinal IPW and AIPW ([#3](https://github.com/etverse/dynamatr/issues/3)).
- Longitudinal structural nested models with transport, oracle-validated censoring weights and a `diagnose()` branch ([#4](https://github.com/etverse/dynamatr/issues/4)).
- Visit-process, grace-period and sequential-positivity diagnostics ([#5](https://github.com/etverse/dynamatr/issues/5)).
- Time-varying treatment weights for survatr's marginal structural hazard model ([#6](https://github.com/etverse/dynamatr/issues/6)).

The methods beyond these are chosen from the literature before the first code.

## Not planned here

- Point treatments: causatr. Time-to-event curves: survatr. Target-trial emulation: emulatr.
