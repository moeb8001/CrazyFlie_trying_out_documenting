# CrazyFlie
Documenting the progress.

# Voice-Controlled Drones with Crazyflie and XIAO ESP32S3

Welcome to the repository for our project focused on using voice commands to control drones through an onboard microphone, utilizing the Crazyflie platform and the XIAO ESP32S3 board.

## Project Overview

- **Project Description:** This project explores the integration of voice commands for drone control using an onboard microphone, offering an innovative approach to drone piloting/safety.

- **Team Members:** 2 for now

## Getting Started

To replicate or contribute to this project, follow the instructions below:
 ** Will upload files soon as we make more progress **



### Installation

- NA


## Progress

This section will be continuously updated to track the progress of our project. Below are key milestones and updates:

### Milestone 1 (Done - kinda)

- Set up the development environment, including the XIAO ESP32S3 board, microphone, and Crazyflie drone.

 

### Milestone 2 (Ongoing)

- Begin gathering data on voice commands and their corresponding actions to fine-tune the recognition system.
- ![image](https://github.com/moeb8001/CrazyFlie/assets/112695184/ab41819b-646a-4891-ac35-3ae571e224a9)
- connected the XIAO ESP32S3 board for recording (trying out):
![image](https://github.com/moeb8001/CrazyFlie/assets/112695184/25368eb6-c401-4f35-b922-67f437a07fb9)

![image](https://github.com/moeb8001/CrazyFlie/assets/112695184/da020335-0e3f-44db-ab8c-1f7a23bcb364)


https://github.com/moeb8001/CrazyFlie/assets/112695184/9ae53417-ec7c-4116-a67a-797fe14547d5

Then found Suryansh open source gimbal CAD files: https://github.com/tristandijkstra/OpenGimbal

The center part obviously had only two arms, in order to prevent creating extra moment of inertia. This is something we did not have to worry about because we just want to have a ** stable + consistent + not moving ** base for recording audio. So I went ahead and made it 4 armed for more stability. 

What I did:
- Made the center hole bigger because the pins didn't fit as shown below:
  ![image](https://github.com/moeb8001/CrazyFlie/assets/112695184/1be08550-6419-486f-94ee-87243b2d09b2)
- Made it 4 armed.

  Here are the after pics:
  ![image](https://github.com/moeb8001/CrazyFlie/assets/112695184/62403e71-4ffe-4515-b862-5a130ba92833)
  ![image](https://github.com/moeb8001/CrazyFlie/assets/112695184/702564a2-c772-4e69-85d4-195637d41b12)
  Now even the charger fits below: ![image](https://github.com/moeb8001/CrazyFlie/assets/112695184/d05576d9-b09d-4b7f-b78f-40a8ffadde4f)

![image](https://github.com/moeb8001/CrazyFlie/assets/112695184/ac88b455-bf87-4fc4-84cc-a577ce33d4ea)







### Milestone 2 (Date TBD)

- Integrate the voice control system with the Crazyflie platform for smooth, real-time drone operation.

## Future Work

Our project is an ongoing effort, and there are several directions we plan to explore in the future:

- (List potential future features or improvements )


## Contact

- (Provide contact information for project leads or maintainers, such as email addresses or GitHub profiles)

Feel free to explore the code and documentation. Your feedback, suggestions, and contributions are highly appreciated!

Thank you for your interest in our project.
