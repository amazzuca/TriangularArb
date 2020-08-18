# TriangularArb
Triangular Arbitrage opportunities checker, based on CCXT framework.
It scans all the exchanges supported by ccxt
for each exchange, it searches all possible legs between coin 1 and coin 3
for each leg it calculates the arbitrage possibility. It doesn't take into account the minimum volumes or the minimum order requirements. 
