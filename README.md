# texas-energy-demand-prediction

## Project Status
This project is currently being worked on of Saturday, Sept 7, 2024.

## Timeline
**Milestone 1** (August 21st): Understand data

**Milestone 2** (August 28th): Data Preperation & feature gathering

**Milestone 3** (September 7th): Regression models trained, learn about LLMs

**Milestone 4** (September 25th): Research tree-based decision making, begin prompt engineering

**Milestone 5** (October 10th): LLM insights from trees

**Milestone 6** (October 20th): Iterate of quality of insights

## LLMs
**Questions that can be answered from the model:** The challenge here is how can you provide the insights from the model & how do you force the LLM to answer in crsp sentences without hallucinating.
- What price should I set it at in order to increase demand of electricity?
- What is the projected demand for tomorrow as provided by the state of Texas?
- Why might this projection be incorrect?
- Would require you to create a model that fixes projections rather than make it's own projections from scratch.

**Questions that can be answered by data:** The challenge here is do you just feed this as context & can the LLM remember this without hallucinating? Or can the LLM infer from other basic data?
- Is generation of electricity scheduled to increase or decrease next week?
- What happens to the mix of gas, solar, & hydro generation over the year?
- Is electricity demand projected to increase year over year?

## What am I looking for?
- A set of automated prompts [python code] that can be used to convert outputs/artifacts from your regression model + parts of raw/ processed data that can be fed into an LLM.
- An intuition for what works, what doesn't work?
- What questions can LLMs answer that I haven't thought of?
