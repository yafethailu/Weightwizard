** Basic Overview of Project **

Recovering from a traumatic lower extremity fracture can be a challenging journey, particularly for patients who must adhere to weight-bearing precautions as part of their rehabilitation process. These precautions dictate the amount of force that can be exerted on the affected limb and vary depending on the type of surgical intervention undergone.
The specific weight-bearing protocols can vary significantly depending on the nature of the surgical intervention, with each patient following a unique trajectory toward their ultimate goal of full recovery and mobility restoration. This entails adhering to a step-by-step progression, typically spanning several weeks or even months, which commences with a mere 10% of weight-bearing (equivalent to 16 pounds) and incrementally advances through stages such as 20% (32 pounds), 30% (48 pounds), 40% (64 pounds), partial weight-bearing at 50% (80 pounds), and culminating in the coveted 100% full weight-bearing status.
Our project partners, Eileen Brodecki and Jennifer Solloway, have given us the opportunity to  develop a device that empowers patients to accurately monitor the amount of weight patients apply to their lower extremity fracture without the need to constantly glance at the floor to check the weight in pounds. This device is particularly valuable during Occupational Therapy (OT) and Physical Therapy (PT) sessions in clinical settings, where clinicians help patients progress in their weight-bearing journey.
Existing solutions, like the use of an analog scale, come with several limitations. These include the necessity for constant visual monitoring and the absence of immediate feedback, which is crucial to prevent the over-weighting or under-weighting of the affected limb. Such limitations can significantly hinder effective rehabilitation. In light of these drawbacks, the impetus for our project gained additional momentum. This was particularly influenced by the practical insights and experiences shared by Bryan, a patient currently undergoing treatment at Streeterville DayRehab. Bryan provided valuable user feedback that highlighted the specific challenges and needs faced by individuals in similar situations, guiding our project's direction.
Our device, Weight Wizard, is designed to assist patients recovering from lower extremity injuries, this device offers an easy and precise method for monitoring weight-bearing progress, eliminating the need for continuous floor monitoring. It features a standard bathroom scale with step-on technology and a wireless display, accommodating up to 400 lbs, thereby ensuring its commercial viability and accessibility. The device integrates key elements such as an Arduino microcontroller with Bluetooth, load cell amplifiers, and a large, clear display, all working in sync to deliver accurate weight readings.
The following sections of the report will include the users, requirements, and specifications for this system, as well as an explanation of the design concept and rationale. Finally, we end with suggested future developments for this design.


** Users and requirements **


Primary User
A patient with a traumatic lower extremity fracture
Our initial primary user, Bryan, was a patient at the Shirley Ryan Ability Lab who had right lower extremity weight-bearing restrictions. His rehabilitation plan required him to incrementally load the injured leg, beginning with static standing to promote healing and progress back to normal activities. The prescribed stress on the limb was to be gradually increased in line with his recovery.


However, during our first user observation, we noted that Bryan had made significant recovery progress, able to walk unaided and nearing full recovery. Consequently, we adjusted our primary user profile to a broader category of patients with lower limb injuries on a similar rehabilitation trajectory.


This shift necessitated our product's design to be adaptable for a wider patient demographic with varied rehabilitation needs, including those with additional challenges such as obesity, color vision deficiency, and hearing loss. The design aim is to ensure our product supports the rehabilitation process effectively for all potential users.
Secondary Users
Physical Therapist (PT)
The physical therapist at Shirley Ryan Ability Lab is Jennifer Solloway. Her task involves working with patients like Bryan to utilize the device to monitor and adjust the weight-bearing load during rehabilitation. 


Occupational Therapist (OT)
The occupational therapist at Shirley Ryan Ability Lab is Eileen Brodecki. She will use the scale’s reading to monitor the patients session, and incorporate into her practice to assess the functional weight bearing capacity of patients as they engage in activities of daily living. 



Requirements
We identified the following requirements for our design during the course of the quarter (see Appendix A):
Simplicity
The device should possess a simple design and concept, enabling users to operate it with minimal instructions. The scale itself should have at most one switch for determining which side the scale should weigh. The display should have at most one switch to turn it on or off. 


Easy Maintenance
It should also have easy-to-open features to facilitate simple fixes and have organized and intuitive wiring for user convenience. Batteries should be easy to replace in both the scale and display. The material used for the scale should be easy to clean, and durable against common cleaning solutions. 


Durability
The device should provide a minimum of 2 hours of battery life, ensuring sustained operation without frequent recharging during therapy sessions. Additionally, it should be capable of securely mounting significant weight, guaranteeing robust and stable support for heavy loads. It should also be reasonably durable against impact. It need not be very resistant against water and dust, an IP rating of around 35. 


Digital Weight Measurement
Instead of a traditional dial display, the device should incorporate digital technology for measuring weight. This will ensure more precise readings and improve visibility for the user.


No Attachable Weights Required 
The design should avoid the need for any additional weights to be attached to the user. This minimizes any extra burden and simplifies the usage process, making it more user-friendly.


Weight Notification
The device should offer visual weight notifications through a multi-color display, where a red light indicates that the weight exceeds the threshold, a yellow light warns of nearing the threshold, and a green light signifies that the weight is below the threshold. Additionally, if possible, we are thinking of considering the inclusion of vibration or sound features. Sound emitted should maintain a non-disturbing volume to avoid inconvenience to the user or their surroundings.
Design Concept and Rationale 




