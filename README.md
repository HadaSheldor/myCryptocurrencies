# myCryptocurrencies
This project has been submitted as part of of a Full Stack Developer programme  and supports a Single Page Application (SPA).
Javascript runs in client-side, containing Ajax requests to coingecko API.
The project's objective is to present an up-to-date information about Cryptocurrencies. 
Data in homepage includes Cryptocurrency's: Name, Symbol, Image, and Current Price (in USD, EUR, and ILS).            
Once mapped, data has been stored locally (client-side) in order to accelerate page loading, yet, since market data changes frequently, storing has been limitted to a timeframe of two minutes in order to invoke a new request to API server.
The project allows users to select up to 5 cryptocurrencies for Live Reports.
Live reports display multi-axes live charts, using jQuery's canvas.js.
