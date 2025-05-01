# 🧠 Trading: CUSUM Filter

Quantitative Researcher | [Mustafa MAJJI](https://www.linkedin.com/in/mustafa-majji-3a59861a2/)

***

## 📚 Project Overview

This project presents an implementation of the CUSUM (Cumulative Sum) filter in Python—an effective statistical technique for detecting structural breaks or regime shifts in financial time series. The CUSUM filter excels at identifying persistent changes in the mean level of a process, making it a powerful tool for event detection, trend analysis, and signal generation in quantitative trading.

By filtering out minor fluctuations, the CUSUM method helps reduce false or noisy signals commonly produced by strategies based on moving averages, thereby enhancing the reliability of trading decisions.

In practice, the CUSUM filter signals a position entry when the cumulative price change exceeds a predefined threshold:

  - A **long position** is triggered when the rate of price increase surpasses a positive threshold.
  - A **short position** is initiated when the rate of price decrease falls below a negative threshold.
    
## 🚀 Repository Structure


- **Images**: Contains all images used in the notebook.

- **CUSUM_FILTER.ipynb**: A Jupyter Notebook that explains and implements the CUSUM filtering process.

## :mailbox_closed: Contact
For any information, feedback or questions, please [contact me][Mustafa-email]




[Mustafa-email]: mailto:majji1999@gmail.com
