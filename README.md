# HiggsPeak_StatsProject

This project aims to reconstruct the Higgs boson discovery signal using its decay into four leptons. Using official open data from CERN (https://opendata.cern.ch/record/12360), the invariant mass spectrum is reconstructed and a signal + background model is fit using Bayesian inference techniques.

---

## Repository Structure

- [`data`](./data)  
  Contains the filtered and processed dataset used for inference.

- [`notebooks`](./notebooks)  
  - Data extraction and filtering from raw CERN files  
  - Bayesian inference and parameter estimation
 
  Note: The `Data_Extraction_General` notebook is computationally expensive and requires large downloads (~10 GB). It is **not necessary** to reproduce the main results.

- [`plots`](./plots)  
  Final figures, including posterior distributions, model fit and reconstructed mass spectrum
