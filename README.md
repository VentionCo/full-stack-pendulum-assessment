## **Problem Statement**  
You are tasked with building a **distributed pendulum simulation** in Node.js, which can be visualized and controlled through a React UI. 
The goal of this exercise is to evaluate your skills in server-side programming, API design, frontend development, and distributed systems coordination. 
The assignment involves both server and client-side components that need to interact seamlessly.

![image](https://github.com/user-attachments/assets/90c4e53d-466e-4bb6-b177-b211cd87e6dd)


## **Checklist of Requirements and Bonus Points**  

### **Mandatory Requirements**  
- **Server-side pendulum simulation using Node.js**  
  - [ ] Implement a Node.js server which runs a single pendulum simulation with configurable parameters for: initial angle, mass, and string length.
  - [ ] Run **five separate instances of this server**, so the full system is **composed of 5 servers**, each responsible for its own pendulum.

- **Neighbor Communication**  
  - [ ] Make each pendulum aware of its neighbors and monitor their positions.  
  - [ ] Define a threshold for collisions; when a collision is detected, send a **STOP message** to all instances.  
  - [ ] After a STOP, the simulation should halt. The pendulum sends a **RESTART message** and waits until all instances receive **RESTART messages** from all other instances, at which point each pendulum waits 5 seconds and **restarts**.  

- **Web-Based UI**  
  - [ ] Build a UI using React to render and configure the pendulums.  
  - [ ] Add basic simulation controls: start, pause, and stop.  
  - [ ] Ensure the UI periodically updates pendulum positions (e.g., every few frames).  

## **Bonus Points**  
- [ ] Provide an **intuitive user experience** for configuring pendulums (starting angle, mass, string length, string anchor).  
- [ ] Use TypeScript for both the frontend and the backend.
- [ ] Add wind to the simulation.
- [ ] Run the whole stack with one single command.
- [ ] Write a few **unit tests** for the REST API and key logic in the Node.js code.
- [ ] Anything else you'd like to impress us with! Have fun!

## **Submission**  
- [ ] Share your solution on **GitHub**.  
- [ ] Include a **README** with instructions on how to run the project.  
