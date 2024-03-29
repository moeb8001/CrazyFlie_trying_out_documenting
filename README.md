# CrazyFlie [Will not be updated anymore due to privacy reasons]
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

- connected the XIAO ESP32S3 board for recording (trying out):
![image](https://github.com/moeb8001/CrazyFlie_trying_out_documenting/assets/112695184/a59fde60-ebc9-4d8f-8801-0f8f483d0bca)
![image](https://github.com/moeb8001/CrazyFlie_trying_out_documenting/assets/112695184/44dbefdb-9e26-4da4-a5e4-89b0b8611428)



![image](https://github.com/moeb8001/CrazyFlie_trying_out_documenting/assets/112695184/2e97b161-9a2e-430a-be3c-7ee687bf6502)


https://github.com/moeb8001/CrazyFlie_trying_out_documenting/assets/112695184/8c094195-ea22-49e6-a2b5-c74b00f21216



Then found Suryansh open source gimbal CAD files: https://github.com/tristandijkstra/OpenGimbal

The center part obviously had only two arms, in order to prevent creating extra moment of inertia. This is something we did not have to worry about because we just want to have a ** stable + consistent + not moving ** base for recording audio. So I went ahead and made it 4 armed for more stability. 

What I did:
- Made the center hole bigger because the pins didn't fit as shown below:
  ![image](https://github.com/moeb8001/CrazyFlie_trying_out_documenting/assets/112695184/9f212b08-3437-4581-8369-61fcd9fcd6d6)

- Made it 4 armed.

  Here are the after pics:
  ![image](https://github.com/moeb8001/CrazyFlie_trying_out_documenting/assets/112695184/95967fae-9cdc-403b-8852-b1f8988515f7)

![image](https://github.com/moeb8001/CrazyFlie_trying_out_documenting/assets/112695184/aebe1011-f102-497f-8fda-d8b6f4c99850)
![image](https://github.com/moeb8001/CrazyFlie_trying_out_documenting/assets/112695184/f36469e9-d113-40ec-bdc3-58685ecf9b83)

![image](https://github.com/moeb8001/CrazyFlie_trying_out_documenting/assets/112695184/3a7ee511-7f85-4b6f-9ade-bc0c9ca276c1)


  Now even the charger fits below:![image](https://github.com/moeb8001/CrazyFlie_trying_out_documenting/assets/112695184/4ccfcf03-45f1-4857-a08b-a3644dc2571a)



Playing around with toroidal proppellers:
They do obviously not as efficient as other normla propellers, but it is good to inverstigate the effect they have on the overall  noise (makig it easier to detecet voice commands)

Also tried resin printing the propellers (more smooth surface):
![image](https://github.com/moeb8001/CrazyFlie_trying_out_documenting/assets/112695184/e7147355-4f5f-42f5-b78d-58fddcd50860)




### Milestone 2 (Date TBD)

- Integrate the voice control system with the Crazyflie platform for smooth, real-time drone operation.
- We used **https://edgeimpulse.com/** for deploying the trained keyword recoginition model onto ESP32S3.

## Future Work

Our project is an ongoing effort, and there are several directions we plan to explore in the future:

- (List potential future features or improvements )


## Contact

- (Provide contact information for project leads or maintainers, such as email addresses or GitHub profiles)

Feel free to explore the code and documentation. Your feedback, suggestions, and contributions are highly appreciated!

Thank you for your interest in our project.
