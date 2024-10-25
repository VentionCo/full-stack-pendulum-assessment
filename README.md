## **Problem Statement**  
You are tasked with creating a simple pendulum simulation in Node.js, which can be visualized and controlled through a React UI. 
The goal of this exercise is to evaluate your skills in server-side programming, API design, frontend development, and distributed systems coordination. 
The assignment involves both server and client-side components that need to interact seamlessly.

![image](https://github.com/user-attachments/assets/90c4e53d-466e-4bb6-b177-b211cd87e6dd)


## **Checklist of Requirements and Bonus Points**  

### **Mandatory Requirements**  
- **Pendulum Simulation in Node.js**  
  - [ ] Implement a simple 1D pendulum simulation with configurable parameters: initial angle, mass, and string length.
  - [ ] Run **five instances** of the pendulum.  

- **Neighbor Communication**  
  - [ ] Make each pendulum aware of its neighbors and monitor their positions.  
  - [ ] Define a threshold for proximity; if neighbors get too close, send a **STOP message** to all instances.  
  - [ ] After a STOP, each pendulum waits 5 seconds and only **restarts** once all instances receive five **RESTART messages**.  

- **Web-Based UI**  
  - [ ] Build a UI using React to visualize the pendulums.  
  - [ ] Add basic simulation controls: start, pause, and stop.  
  - [ ] Ensure the UI periodically updates pendulum positions (e.g., every few frames).  

## **Bonus Points**  
- [ ] Provide an **intuitive user experience** for configuring pendulums (starting angle, mass, string length).  
- [ ] Use **WebSockets** for real-time UI updates instead of polling.  
- [ ] Use TypeScript for both the frontend and the backend.
- [ ] Run the whole stack with one single command.
- [ ] Write a few **unit tests** for the REST API and key logic in the Node.js code.

## **Submission**  
- [ ] Share your solution on **GitHub**.  
- [ ] Include a **README** with instructions on how to run the project.  
