# VRP_playgrounds
Collection of simulators for fleet management/ food delivery problem that can be generalized to dynamic vehicle routing problem.

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
  - Running time: More than 2 hours for simulating 9:00-12:00 on a laptop with Rayzen 9 CPU.
  - Issues: The simulation is getting slower and slower as more idle vehicles are loaded.
2. fleet_sim, [link](https://github.com/hitsuji5/fleet-sim)
3. FleetAI, [link](https://github.com/hitsuji5/FleetAI)
  - Not runnable, the scikit-image cannot be installed, 12/16/2021.
4. IDQ_HEX, [link](https://github.com/sguo28/IDQ_HEX/tree/master/code)


