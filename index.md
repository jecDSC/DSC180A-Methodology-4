# <center>Jeremy Cho</center>

### <center>jec056@ucsd.edu</center>

---

## <center>D17 - Physical Intelligence for Intelligent Manufacturing</center>

### <center>Tauhidur Rahman</center>

1. What is the most interesting topic covered in your domain this quarter?
   **It was interesting to see how to apply reinforcement learning to drones so that they can make up for physical degradation. The most common experiment I saw across different papers was motor failure, and there were several different ways to train the drone to compensate for it, such as using external sensors or image data. Our focus is on whether a drone can adapt to degradation using exclusively drone state data, such as position, velocity, and any other data collected through a drone's interial measurement unit.**

2. Describe a potential investigation you would like to pursue for your Quarter 2 Project.
   **So far, our focus is on the four different controller/RL algorithm combinations and comparing the performance of each against each other. We have a basic, uniform path that a drone follows for several runs of fault severity. We could aim to push the limits of the controller types by simulating different external conditions, such as wind or obstables. Varying the drone flight paths would also allow us to see how applicable our controllers are to different situations.**

3. What is a potential change you’d make to the approach taken in your current Quarter 1 Project?
   **Up to the checkpoint, we focused on ensuring we have an easily accessible and operable workflow than any group member can use to run the drone simulations. I feel that now is the time where we pivot to testing different conditions than the ones we already proposed while we improved the workflow files. More specifically, we want to ensure we have an abundance of data to work with collected from a variety of experimental conditions. The question of whether reinforcement learning improves drone control has been explored by many others, so we should make sure that our experimental conditions haven't been explored yet to the best of our knowledge.**

4. What other techniques would you be interested in using in your project?
   **Currently, we have 26 pieces of data that a policy looks at for every timestep for an update. We plan to run ablation tests to see what set of data is the most crucial for a policy and controller to work the most optimally. We may also try to control how much residual from a proximal policy algorithm we can feed into the drone controller and see how significant of a change in performace is found.**
