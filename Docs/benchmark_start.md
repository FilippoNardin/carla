Agent Benchmark
===============

One of the main objectives of CARLA is to serve as a comparison
tool for driving controllers in reproducible pre-determined conditions.
With this, the *agent benchmark* module operates as a way to use CARLA
to evaluate certain driving controller (agent) and obtain a some
metrics about its performance. 

Getting Started
----------------

To run an example of a trivial agent performing in an small
set of experiments run:

    $ ./benchmark_example.py


Keep in mind that to run the command above, you need a CARLA simulator
server running, on  localhost and on port 2000.
    

We already provide the same benchmark used in the CoRL
2017 paper. By running this benchmark you can compare the results of your agent
to the results obtained by the agents shown in the paper. 
The CoRL 2017 experiment suite can be run in a trivial agent by
running:

    $ ./benchmark_example.py --corl-2017

This benchmark example can be further configured. Run the help command to see options available.

    $ ./benchmark_example.py --help


Next we show how to  set up your agent and customize the conditions
where it will be tested.


