# SwapCurve

Interest rate curves have many different types. Sometimes they are quite confusing. There are two main categories in the market: market observed interest rate curves and derived interest rate curves.

Market observable interest rate curves are mainly swap curves and bond curves. They consist of market observable quotations, such as bond prices, swap rates, basis swap spreads, interest rate futures prices, or deposit rates. Bond curves are the term structure of market quoted bond prices, while swap curves are the term structures of swap rates, basis swap spreads, or Eurodollar futures. Swap curves can be futher divided into base swap curves and basis swap curves. Normally the 3 month swap curve is the base curve as all the basis curves are quoted against it. The market observable curves cannot be used for valuation directly. Thus they need to be bootstrapped into the derived curves that are essential for asset pricing.

Derived interest rate curves are mainly yield curves. Yield curve is the term structure of interest rate yields-to-maturity. Yield curve is widely regarded as the best proxy for risk-free curve and benchmark curve. Liquidity of underlying instrumennts is crucial. Since the swap market is a very liquid market with narrow bid-ask spreads and a wide selection of maturities, yield curves derived from swap curves offer several advantages over government curves (e.g., treasury yield curve). With the supply of government bond issues declining, yield curves are mainly bootstrapped from swap curves.

Swap curves can be categoried into swap rate curves, basis curves, and OIS curves. Usully a swap rate curve is also called a base curve or standard curve or 3 month swap curve. The reason for calling 3 month curve as base curve is all the other (basis) curves are quoted against it.

The swap rate curve consists of a set of the most liquid and dominant interest rate products for certain time horizons. Normally the curve is divided into three parts. The short end of the term structure is determined by deposit rates. The middle part of the curve uses Eurodollar futures or FRAs. The far end is given by mid swap rates.

reference

https://finpricing.com/lib/IrCurveIntroduction.html
