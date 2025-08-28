# Titan Valuation under Tariffs & Fed Rate Shocks

This repository explores how **macroeconomic shocks** such as **U.S. tariffs on Indian jewellery exports** and **Federal Reserve interest rate hikes** affect the valuation of **Titan Company Limited**.  

Using Python, I model the impact of changes in **WACC (Weighted Average Cost of Capital)** on company valuation. The project combines **financial theory with coding** to demonstrate how sensitive valuations are to policy and rate shifts.  

## Project Overview
- **Context**:  
  - U.S. tariffs on Indian jewellery exports = 25–50% vs. only 10% from UAE.  
  - Titan exploring shifting manufacturing to the Gulf (leveraging its $283M Damas acquisition).  
  - Fed hiking rates → U.S. Treasury yields (10Y ~4.6%, 30Y >5%) → higher global risk-free rate.  

- **Goal**:  
  Quantify how these shocks (tariffs + Fed hikes) flow into Titan’s **cost of capital** and ultimately its **intrinsic valuation**.  

- **Methodology**:  
  1. Build a Python model to calculate WACC.  
  2. Simulate different scenarios:  
     - Tariff hikes (affecting Rf and discount rate).  
  3. Plot valuation sensitivity to WACC changes.  

## Tech Stack
- **Python**  
- Libraries:  
  - `pandas` (data manipulation)  
  - `numpy` (financial math)  
  - `matplotlib` (charts/visualization)  
  - `yfinance` (market data for risk-free rates, betas, etc.)  

## Sample Output
A typical chart shows how Titan’s valuation declines as WACC increases due to:  
- Higher **risk-free rates (Rf)** from Fed hikes.  
- Higher **equity risk premium** from tariffs and geopolitical shocks.  

## Key Learning
- **Valuation is not static** — even small changes in Rf or risk premiums can shift intrinsic value meaningfully.  
- Companies like Titan actively hedge policy shocks (e.g., manufacturing shift to Gulf) to manage risk.  
- Demonstrates the **intersection of macroeconomics, corporate strategy, and quantitative finance**.  
