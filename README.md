# The-Senate-Bus-Problem
Implement the modified Senate Bus Problem in C language (you can be inspired by The Little Book of Semaphores).
The riders are coming to a stop and waiting for a bus. At the time of arrival
the bus will board all pending people. Bus capacity is limited. If it's on the platform
more people than bus capacity are waiting for people who have not already been to the bus to another bus.
If there is a bus stop on the bus stop and the persons present at the stop are coming, the other arrivals always
waiting for another bus. Upon arrival, the bus leaves. If nobody arrives at the stop
does not wait, the bus leaves empty.
Example: The bus capacity is 10, the waiting persons are 8. The bus arrives, the passengers are coming, they come
another 3 people. There are only 8 waiting people, the bus leaves and the newly arrived 3 people are waiting at the stop.

Execution:
$ ./proj2 R C ART ABT
where:
• R   is number of riders;                                              R > 0.
• C   is capacity of the bus;                                           C > 0.
• ART is maximal time (in ms), after new process of rider is generated; ART >= 0 && ART <= 1000.
• ABT is maximal time (in ms), for which the bus is simulating ride;    BT >= 0 && ABT <= 1000.

All parameters are integers

You can find more in task.pdf (for english google translate usually works quite good but not always perfectly :/)
