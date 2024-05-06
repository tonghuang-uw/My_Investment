# My Investment Analysis

## Project Overview

This project centers on the construction and optimization of a financial portfolio employing a top-down strategy, inspired by methods described in Rob Carver's book Smart Portfolio. The portfolio is segmented into Equity and Bond categories, subdivided by region and type. The notebook entails data retrieval, computation of returns, volatility, covariance, and correlation matrices, coupled with portfolio optimization techniques to pinpoint minimum variance and efficient frontier portfolios. My goal is to utilize this notebook to make informed personal investment decisions, maintaining updates with any alterations to my portfolio strategy.

As an investor, I aim to maximize my equity exposure while achieving substantial diversification with minimal time investment.

## Contents

Drawing from Rob Carver’s insights, traditional mean-variance portfolios often result in extreme weight distributions. For example, the maximum return portfolio might heavily favor US equity, whereas the minimum variance portfolio might predominantly lean towards US bonds. This notebook demonstrates these tendencies clearly even before applying sophisticated optimization techniques.

Carver advocates for a diversified portfolio framework, presuming equal risk-adjusted returns across assets, enhanced by a factor multiplier applied to risk weights, which are then converted to cash weights. In this notebook, I incorporate a momentum factor, assigning increased weight to assets that have appreciated in value over the past year. This is achieved by calculating the trailing Sharpe ratio, which then informs the multiplier adjustments for the initial risk weights.

## Asset Selections

Employing a top-down approach, I decided to invest predominantly in equities, configuring the portfolio with a high-risk, high-return allocation of 90% in equities and 10% in bonds. The equity investment is evenly distributed among US, European, Asian, and Global Emerging Markets. Bond investments are similarly distributed among Government Bonds, Corporate Bonds, High Yield Bonds, and Emerging Market Bonds. After adjustments, the portfolio's final allocation stands at 87% in equities and 13% in bonds, reflecting an aggressive investment stance optimized for growth.

### Assets

#### Equity
* US Equity: IVV
* UK Equity: EWU
* EU Equity: FEZ
* ASIA Equity: VPL
* Emerging Market: VWO

#### Bond
* Goverment Bond: GOVT
* Corperate Bond: VCIT
* High Yield Bond: USHY
* Emerging Market: VWOB

## Investment Philosophy and Strategy

My investment strategy is aggressive, prioritizing high equity exposure and embracing the volatility associated with high growth markets. The strategic weighting and reallocation based on recent performance metrics align with a dynamic investment philosophy that adapts to market trends while aiming for robust long-term returns.

## Updates and Monitoring

I commit to regularly updating this portfolio analysis to reflect any strategic adjustments or shifts in the market conditions. This continuous monitoring and adaptation are vital for aligning the portfolio with my financial goals and risk tolerance.

