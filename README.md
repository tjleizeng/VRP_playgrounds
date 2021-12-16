# VRP_playgrounds
Collection of simulators for fleet management/ food delivery problems that can be generalized to (dynamic) vehicle routing problems.

TODO list:

- [ ] Test 2, 3 and 4.
- [x] Write a short description for 1.
- [ ] Collect more simulators.
- [ ] Add a table that summarizes all simulators.

## Key takeaway 

List of simulators:

1. mdrp_sim, [link](https://github.com/sebastian-quintero/mdrp-sim)
  - Key features: multiple scenarios, real-world data, route engine, order cancellation, time window, vehicle offline, proactive repositioning.
  - Key assumptions: deterministic unchanged travel time; occupied vehicle (though not full) would not receive notification.
  - Running time: More than 5 hours for simulating 9:00-12:00 (around 400 vehicles and 200 requests) on a laptop with Rayzen 9 CPU.
  - Issues: The simulation is getting slower and slower as more idle vehicles are loaded.
2. fleet_sim, [link](https://github.com/hitsuji5/fleet-sim)
3. FleetAI, [link](https://github.com/hitsuji5/FleetAI)
  - Not runnable, the scikit-image cannot be installed, 12/16/2021.
4. IDQ_HEX, [link](https://github.com/sguo28/IDQ_HEX/tree/master/code)
5. simobility, [link](https://github.com/sash-ko/simobility)
6. Cargo, [link](https://github.com/jamjpan/Cargo)
7. Last-mile-delivery-problem, [link](https://github.com/yongyanghz/Last-mile-delivery-problem)
8. tsp_real, [link](https://github.com/prathyaksh03/tsp_real)
9. VehicleRoutingProblem, [link](https://github.com/shlok57/VehicleRoutingProblem/tree/master/Genetic2)
10. pdptw-instances, [link](https://github.com/cssartori/pdptw-instances)
11. ride-sharing-simulation, [link](https://github.com/Vardominator/ride-sharing-simulation)
12. Self-driving-electric-ride-hailing-simulation-deep_learning-optimization, [link] (https://github.com/lianghu83/Self-driving-electric-ride-hailing-simulation-deep_learning-optimization)
13. Ride-hailing-batching-simulation, [link](https://github.com/juanhu96/Ride-hailing-batching-simulation)



