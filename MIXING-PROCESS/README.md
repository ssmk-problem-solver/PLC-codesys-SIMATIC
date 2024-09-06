# ---------------------------------------

Mixing and filling application. It is the extension of previous example. There are two push buttons I0 and I1 for start and stop (both push buttons are NO type/ green in physical existence). There are three level switches I2, I3, I4 and I5 for low level, middle level high level and bottle detector sensor respectively. There are 3 valves; V1/ Q0 for material 1, V2/ Q1 for material 2 and V3/ Q3 for drain. There is a motor for mixing two materials in the mixing tank and one conveyor Q4. When I0 is pressed, Q0/ V1 will get on resulting material 1 inlet to mixing tank. As material 1 comes in mixing tank, low level sensor I2 will get on and further middle level sensor I3 will be on. As I3 is on, Q0/ V1 should get off and Q1/ V2 should get on. As V2 is on, material 2 will come in mixing tank resulting increase in level and reaches to I4 sensor. As I4 is on, Q1/ V2 will get off and motor Q2 will get on for 10 seconds. After 10 seconds, motor gets off and conveyor Q4 gets on. Bottle to be filled will move on it. As bottle will be detected by I5 sensor, conveyor Q4 will stop and drain V3/ Q3 will get on for 5 seconds. After 5 seconds again conveyor will be on and drain will get off. Whenever I5 detects bottle, the same cycle of conveyor and drain will repeat. As drain will get on many times, mixing tank will start getting empty. Slowly level will go down resulting I4 off, I3 and I2 sensors off one by one. As I2 is off repeat the process. I1 is manual stop.

# ---------------------------------------





![WhatsApp Image 2024-02-06 at 20 35 13_c7cece49](https://github.com/user-attachments/assets/fe41194e-5cfe-414b-bd7d-9aad3c39b89b)

