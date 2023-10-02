# simIDM 0.0.5.9011

- ExpSurvOS now returns 0 instead of NaN for large values of t (#73, @holgstr)

# simIDM 0.0.5.9011

- First CRAN version of the package.
- The package simulates illness-death models with constant, Weibull or piecewise constant transition hazards.

### New Features

- Exponentially, Weibull and piecewise exponentially distributed survival times.
- Random censoring and event-driven censoring after a pre-specified number of PFS or OS events.
- Arbitrary number of treatment arms and flexible randomization ratio.
- Staggered study entry.
- Derivation of PFS and OS survival functions from transition hazards.