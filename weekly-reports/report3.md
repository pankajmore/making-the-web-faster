% Weekly Report 3
% Pankaj More (Y9227402)
% 11th March, 2013

# Papers Read

* Armbrust, Michael, Armando Fox, Rean Griffith, Anthony D. Joseph,
  Randy Katz, Andy Konwinski, Gunho Lee et al. "A view of cloud
  computing." Communications of the ACM 53, no. 4 (2010): 50-58.

* Abts, Dennis, and Bob Felderman. "A Guided Tour through Data-center
  Networking." Queue 10, no. 5 (2012): 10.

# Summary

The first paper starts with a clear and precise definition of the term
"cloud computing". Then it gives a list of specific features that are
only applicable to cloud computing and not conventional data
centers. One important benefit of cloud computing that was new to me
was the concept of "cost associativity". It simply means using 10000
server X 1 hr costs the same as using 1 server for 10000 hours. It
helps save a lot of time in large compute-intensive tasks without
incurring additional costs. Reading the paper, it looks like for new
services with flexible requirements , cloud computing is downright
essential and not just a feature to have and not using cloud
computing's advantages might feel like competing with advanced aliens
with magical technologies. The paper also emphasizes on top 10
obstacles for widespread adoption of cloud computing especially in the
enterprise and also hints at how those obstacles can be solved and
what opportunities lie in solving those problems.

The second paper talks about networking issues inside a
data-center. It distinguishes between two kinds of flows "elephant"
flows and "mice" flows. Understanding the impact of "elephant" flows
on traffic requirements is essential for optimal traffic planning. The
network topology plays a very important role in designing efficient
data center networks. It affects many parameters such as performance,
path diversity, redundancy, fault resilience, average and maximum
cable length and cost. There are mutual trade-offs between these
parameters which makes the problem exceedingly hard. Conventional
layer 2 and layer 3 routing algorithms are quite unsuitable and new
routing algorithms like VL2 and PortLand have been proposed. We will
look at these algorithms in future readings.
