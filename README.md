# VRP_playgrounds
Collection of simulators for fleet management/ food delivery problems that can be generalized to (dynamic) vehicle routing problems.

TODO list:

- [x] Test 2, 3, 4, 5, 6.
- [x] Write a short description for 1.
- [x] Collect more simulators.
- [ ] Add a table that summarizes all simulators.

## Key takeaway 

List of simulators:

1. mdrp_sim, [link](https://github.com/sebastian-quintero/mdrp-sim)
  - Key features: multiple scenarios, real-world data, route engine, order cancellation, time window, vehicle offline, proactive repositioning, results stored in postgresql.
  - Key assumptions: deterministic unchanged travel time; occupied vehicle (though not full) would not receive notification.
  - Running time: More than 5 hours for simulating 9:00-12:00 (around 400 vehicles and 200 requests) on a laptop with Rayzen 9 CPU.
  - Issues: The simulation is getting slower and slower as more idle vehicles are loaded.
2. fleet_sim, [link](https://github.com/hitsuji5/fleet-sim)
  - Key features: real-world data, route engine, customer leave, vehicle offline, vehicle cruising, results stored in sqlite
  - Key assumptions: determinsitic unchanged travel time; single customer per vehicle (no ridesharing).
  - Running time: 6 minutes for 5 hours' simulation (with at most 5000 vehicles, 600 occupied vehicles, and 50 requests/step) on a laptop with Rayzen 9 CPU.
  - Issues: The data preprocessing take a long time; some places are not connected in osrm, which causes errors.
3. FleetAI, [link](https://github.com/hitsuji5/FleetAI)
  - Not runnable, the scikit-image cannot be installed, 12/16/2021.
4. Adapool, [link] (https://github.com/marina-haliem/AdaPool) and DRSP-Sim, [link](https://githubmemory.com/repo/marina-haliem/Dynamic-RideSharing-Pooling-Simulator)
  - Key features: Extending the 2.fleet_sim with pricing and ridesharing modules, introducing new learning-based algorithms.
  - Issues: The documentation attributes to 3.FleetAI instead of the references for 2.fleet_sim, which seems to be incorrect.
5. IDQ_HEX, [link](https://github.com/sguo28/IDQ_HEX/tree/master/code)
  - Key features: Extending the Adapool by adding hexagon map and parallel computing, introducing new learning-based algorithms.
  - Issues: Currently not runnable since the log file suggested the some variables are missed in the config file.
6. simobility, [link](https://github.com/sash-ko/simobility)
  - Key features: Light weight, route engine.
  - Running time: The author provided a running time table.
  - Issues: Not runnable as it would return the error "cannot import name 'BasePosition' from 'simobility.core'".
7. Cargo, [link](https://github.com/jamjpan/Cargo)
8. Last-mile-delivery-problem, [link](https://github.com/yongyanghz/Last-mile-delivery-problem)
9. tsp_real, [link](https://github.com/prathyaksh03/tsp_real)
10. VehicleRoutingProblem, [link](https://github.com/shlok57/VehicleRoutingProblem/tree/master/Genetic2)
11. pdptw-instances, [link](https://github.com/cssartori/pdptw-instances)
12. ride-sharing-simulation, [link](https://github.com/Vardominator/ride-sharing-simulation)
13. Self-driving-electric-ride-hailing-simulation-deep_learning-optimization, [link] (https://github.com/lianghu83/Self-driving-electric-ride-hailing-simulation-deep_learning-optimization)
14. Ride-hailing-batching-simulation, [link](https://github.com/juanhu96/Ride-hailing-batching-simulation)



