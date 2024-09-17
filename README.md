# Python codes to calculate back azimuths of retrograde Rayleigh waves (Hirose_and_Ueda_2024JGR)

## Description
This repository contains the functions used in Hirose and Ueda (2024) along with an example.
- example folder:
  - polanalysis_example_120s.py: Main code to estimate back azimuths of retrograde Rayleigh waves for 2-minute window.
  - core folder:
    - backazimuth.py: Function to estimate back azimuths.
  - nipfilter folder:
    - core.py: Functions for s-transform.
    - filter.py: Functions to calculate instantaneous propagation angles and NIP values.
    - st.py: ctypes interface to st.c
    - st.c: C code for s-transform.
  - 

