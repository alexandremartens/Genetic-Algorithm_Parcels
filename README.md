# Genetic-Algorithm_Parcels

  info section explains the behaviour of the algorithm<br />
  Using values? -> Section 2<br />
  Using only A,B,C without values? -> Section 1<br />
  Using the brute will modify the way the Simulation method places the parcels<br />
  Using the bruteforce will modify the way the Simulation method places the parcels. advised to keep it 'True'<br />


  ## Section 1 
  Step 1.0: fill A,B,C number of parcels <br />
  Step 1.1: set the boolean ValueBoolean = false;<br />
  Step 1.2: Add a time-limit of execution in milliseconds.<br />
  Step 1.3: RUN the program<br />

  info 0.0: Volume total parcels > container volume?<br />
    --> Will say you can't use that number of parcels<br />
  info 1.0: Volume total parcels <= container volume<br />
  info 1.1: Volume total parcels = container volume and all parcels CAN be placed<br />
    --> Will find the container, all filled<br />
  info 1.2: Volume total parcels < container volume and all parcels CAN be placed<br />
    --> Will find the container, with gaps obviously<br />
  info 1.3: Volume total parcels < container volume and all parcels CAN't be placed<br />
    --> Will remove some pieces and try to get the most pieces placed, will stop with the time-limit<br />

  ## Section 2
  Step 2.0: fill A,B,C number of parcels, if unlimited write values 60,44,50 respectively<br />
  Step 2.1: fill A,B,c's respective weights<br />
  Step 2.2: set the boolean ValueBoolean = true;<br />
  Step 2.3: Add a time-limit of execution in milliseconds.<br />
  Step 2.4: RUN the program<br />

  info 0.0: Volume total parcels > container volume?<br />
    --> Will stop after the timeLimit and show the best result<br />
  info 1.0: Volume total parcels <= container volume<br />
  info 1.1: Volume total parcels = container volume and all parcels CAN be placed<br />
    --> Will find the container, all filled and show the best result<br />
  info 1.2: Volume total parcels < container volume and all parcels CAN be placed<br />
    --> Will find the container, with gaps obviously and show the best result<br />
  info 1.3: Volume total parcels < container volume and all parcels CAN't be placed<br />
    --> Will stop after the timeLimit and show the best result<br />
