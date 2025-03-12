### Longitudinal study for alien growth process
This study examines the growth patterns of an alien species with human-like physiology using longitudinal data collected over two generations. In the first generation, the standing heights of Cohort 1 subjects were recorded from birth to around age 20. The second generation tracked the heights and weights of their progeny (Cohort 2) from birth to age 18. The dataset presents several challenges, including irregular measurements, missing data, subject dropout, and potential data contamination, requiring careful handling and documentation.

```sh
brew install uv
cd longitudinal
uv venv
uv sync
source .venv/bin/activate
uv pip install -e .
uv sync
```
