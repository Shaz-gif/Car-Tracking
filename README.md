# Car-Tracking
This project involves designing car agents for a driverless car using a simple sensor to locate other cars and drive safely. The main tasks include:

1. **Emission Probability:** Implementing the probability of observing a noisy measurement from a microphone, and updating the probability of each tile given the observed distance. This allows the car to locate stationary cars using the noisy sensor data.

2. **Transition Probability:** Learning the transition probability, which is the probability of a car being in a new location given its previous location. This is learned by observing cars driving around different maps.

3. **Particle Filter:** Implementing a particle filter to track moving cars more efficiently, especially on larger maps. The particle filter reduces computational complexity compared to exact inference.

4. **Autonomous Driver (Optional):** Developing an autonomous driver that can navigate the car safely from start to finish. The autonomous driver avoids tiles where there may be cars and follows a goal-directed path, potentially using learned transition probabilities.

Overall, the project aims to create a robust and efficient driverless car agent capable of safely navigating various environments while minimizing the risk of accidents.
