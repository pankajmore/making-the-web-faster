% Weekly Report 2
% Pankaj More (Y9227402)
% 4th March, 2013

# Papers Read

* Cheng, Yuchung, Nandita Dukkipati, and Matt Mathis. "Proportional
  Rate Reduction for TCP." (2012).

* Dukkipati, Nandita, Tiziana Refice, Yuchung Cheng, Jerry Chu, Tom
  Herbert, Amit Agarwal, Arvind Jain, and Natalia Sutin. "An argument
  for increasing TCP’s initial congestion window." ACM SIGCOMM
  Computer Communication Review 40, no. 3 (2010): 27-33.

* Mathis, Matt. "Laminar TCP and the case for refactoring TCP
  congestion control." (2012).

* Langley, A., N. Modadugu, and B. Moeller. "Transport Layer Security
  (TLS) False Start." (2010).

* Langley, Adam. "Transport Layer Security (TLS) Next Protocol
  Negotiation Extension." (2012).

* Contavalli, Carlo, Sean Leach, Edward Lewis, and Wilmer van der
  Gaast. "Client subnet in DNS requests." (2012).

* Belshe, Mike, and Roberto Peon. "SPDY Protocol." (2012).


# Summary

A lot of these papers are really well deployed already and being used
in real world. Some of the important ideas learnt include :

* Using data-driven analysis to arrive at the optimal value of TCP's
  initial congestion window and supporting those decisions with
  justifications based on domain knowledge.

* Re-factoring and abstracting TCP Congestion algorithms such that
  they are easier to reason about and novel mathematically "tractable"
  algorithms can be proposed on top of such a model. Separation of
  concerns related to transmission scheduling and TCP congestion
  control is especially helpful as described in "Laminar TCP"

* A novel hybrid approach to TCP congestion control that adjusts its
  cwind size proportional to the network state rather than being too
  aggressive or too passive(existing older congestion control algorithms).

* TLS False start is similar to TCP Fast Open in the sense that it
  tries to save one RTT by sending data even before a TLS handshake is
  complete. 
