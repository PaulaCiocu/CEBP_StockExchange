Stock Exchange

Simulate or implement a stock exchange where shares are traded. The shares belong to various companies listed on the exchange. Transactions are conducted by buyers and sellers of shares as follows:

    - Sellers offer a number of shares for sale and specify a certain price per share.
    - Buyers express their intention to purchase a number of shares at a specified price.
    - When an offer matches a corresponding request in terms of price, a number of shares, n = min (offer, request), are traded.
    - Everyone has access to information related to offers and requests, as well as the transaction history.
    - Requests and offers can be modified at any time if there is no ongoing transaction for the relevant shares.

By implementation, we mean a distributed system (server and clients) in which clients are sellers and buyers. By simulation, we mean a program in which sellers and buyers are simulated through threads of execution based on algorithms that take into account common information (requests, offers, list of completed transactions).
