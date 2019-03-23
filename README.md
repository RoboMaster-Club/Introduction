# Purdue Robomaster Club Funding Proposal

### What is Robomaster?

RoboMasters is the world’s **largest**, most **complex**, and completely over-the-top **university level robotics competition**. **Since 2015**, students from all over the world have competed in this multi-stage robot- ics competition that takes place annually in Shenzhen, China. In 2017, **more than 200 universities and 10,000 students participated in the competition that was viewed by nearly 30 million people**. Robo- Masters highlights the importance of teamwork, innovation, communication and technical skills, and leadership which are essential skills for young engineers to develop.

![image-20190321160852151](/Users/ChengMing/Library/Application Support/typora-user-images/image-20190321160852151.png)

**Robomasters has been growing in China and Internationally since 2015.** In China, competition is intensely promoted. They have a reality TV show, [an animated TV series](https://www.twitch.tv/videos/285502734), documentaries, and comics all linked with the competition. Last year, the organizers reported that over 30 million people viewed the competitions across multiple platforms.

**This competition is also growing internationally.** Two years ago there were only a couple of international teams, last year there were **12**, and this year there are **23**. We believe that getting in early and establishing a strong team will greatly benefit Purdue in the long run. Robomasters has been highlighted by many news sources including  ["the Verge"](https://www.theverge.com/2016/9/27/13059144/dji-robomasters-robot-drone-battle-video-frank-wang-interview) and ["Bloomberg"](https://www.bloomberg.com/news/videos/2019-01-17/china-s-high-stakes-robot-wars-video) as an exciting and emerging robotics education platform. It has also been called the **next college sport.** 

**To know more about how exactly the game is played**, [here is a short video from Youtube](https://www.youtube.com/watch?v=LyYsCyMC-0w)



## Club Introduction

Founded by a group of Purdue engineers in **2017**, Purdue Robomaster Club is one of the most **diverse** and innovative student run robotics club at Purdue University. 

Purdue Robomasters club is a **student-centered** team focused on implementing **cutting edge technology into the design, manufacturing, and programming** of a team of 6 robots and one aerial drone for participation in the international RoboMasters competition.

Students will need to transcend beyond their knowledge of engineering fundamentals to build a robust mechanical system, develop advanced autonomous control algorithms to enhance robot performance, and **collaborate across disciplines**.

![WechatIMG39827](/Users/ChengMing/Desktop/WechatIMG39827.jpeg)

Our club has grown a lot in the past year. We started in early 2018 with about 15 students and have grown to **78 members** this semester. Last year we were able to meet the minimum qualifications to compete and sent 9 students to China for 2 weeks to compete at the competition. **We came back with 3rd prize and high ambitions for this year.** 

**To improve our standing we have been working on building a sponsor network to fund our efforts of building all 7 robots this year** and also rent space to practice and fine-tune our robots. 



![image-20190321161002715](/Users/ChengMing/Library/Application%20Support/typora-user-images/image-20190321161002715.png)

*The picture above is the our team in the 2018 robomaster competition in ShenZhen China during mid-July.* 



## Robomaster Team Introduction

#### Control Team

In control team, we eliminate the gap between human and a robot. By collecting sensors data coming from other teams and making decision internally, operator’s  command could be understood and realized by a machine as if it’s alive robot. By applying control theory, such as PID design based on model dynamics, one is able to regulate system even if it has inherent complexity. Three main topics are going on in control team: drive system dynamics analysis followed by velocity and position control, gimbal stability control and improvement, and prediction on projectile trajectory. Based off these topics, our undergraduate students are developing innovative solutions to make the robot stronger. For example, one of the teammates was able to design a dodge mode for the robot drive system such that it could avoid most of damage during the completion. More and interesting topics are welcome and we certainly need your input and ideas.

#### Electrical Team

Our electrical team is the backbone of the robot which connects the computer vision team hardware, the control team hardware together and provides stable power at the same time. The electrical team also design and implement the sensor on the robot which can provide insight to the player for things like the distance to the wall, and it can also automate some complicated process such as climbing the stair and pick up the ammo box. One of the highlights of the electrical team project is the super-capacitor booster which enables a robot to accelerate much faster during a time of need, around 5-6x faster. The electrical team member implements and design most of the embedded system on board, they also custom design PCB for all the sub-system.

#### Computer Vision Team

Computer Vision team aply technics of computer vision and help the robot to detect the enemy. We take a depth image and feed into a neural network that we have trained before. After we got the position and distance of the enemy, we run a aerodynamics model to solve for the yaw and pitch to hit the target. Last but not least, the yaw and pitch is send to the control algorithm using UART.

#### Mechinical Team

The mechanical team is the backbone of our club. With over 30 members, mechanical team design, prototype and manufacture all robots. Using Solidworks, members design all mechanical parts and combine electrical parts into digital assembly that provide a platform for all other teams to perform their magic. Our ultimate goal is for members to design for manufacturing. As we utilize different manufacturing methods including 3D printing, CNC milling, Water-jet cutting, members not only gain knowledge on how to operate the machines outside of classroom, but also improve their ability to designing CAD and prepare themselves to become better engineers.

Members will also learn to design an efficient manufacturing process and perform basic failure mode analysis to prevent potential hazards and malfunctions.

#### Gaming and Strategic Team

The gaming and strategic team are composed of a group of the robotic engineer as well as an MMORPG (Massively multiplayer online role-playing game) player. Due to the similarity between the gaming MMORPG experience and the Robomaster way of robot control, people who are experienced in MMORPG are extremely good at controlling the robot. This team only available during spring when the robot will be built. The team member of this team will be the final pilot of the robot during the annual RoboMaster Robotic Competition in mid-July.



## We Research



![image-20190321191003108](/Users/ChengMing/Library/Application Support/typora-user-images/image-20190321191003108.png)



#### Research by team

* Computer Vision team <Main Objective: Object Detection>
  * OpenCV Object Detection with various classifiers (Cascade Classifier, SVM) 
  * CNN for object Detection
  * YOLO for object Detection
  * Github Link: https://github.com/RoboMaster-Club
* Mechnical Team <Main Objective: Mechnical Design and Manufacturing>
  * Firing Mechanism Design
  * FEA for the stability and reliability of structures
  * Quadruped Robot Design
  * Material Testing
  * Parts Service Life Study
  * Weight Reduction & FEA on 3D Printing parts
* Electrical Team <Main Objective: Design and build custom electronics for robot>
  * Embedded Circuit Design
  * Sensor Integration
  * Electrical System Control
  * Heads Up Display for high intensity robotic game
  * Super-Capacitor Enabled Electrical Motor Booster with regenerative braking 
  * Customize robot controller board design.
  * Github Link: https://github.com/RoboMaster-Club
* Control Team  <Main Objective: Design and test control alogrithm>
  * Gimbal System ID + Robust Control 
  * Projectile trajectory prediction
  * Adaptive control for drive system

#### Research Papers by member

* Online System Identification of Adaptive Optimal Control On a Four-wheel Mecanum Mobile Robot

  * By Purdue Robomaster Club member **Bo JI** 
  * **This paper is attached to the email**

* Predicting trajectories of a projectile using System ID

  * By Purdue Robomaster Club member **Tianqi Ye**
  * **This paper is attached to the email**

* System Identification of the Gimbal System

  * By Purdue Robomaster Club Member **Yang Ding**
  * **This paper is attached to the email**

## Education Program

## Introduction to our Robots

#### ![WechatIMG2586](/Users/ChengMing/Desktop/WechatIMG2586.jpeg)

*The image above is the rendering of our current generation of robots. On the left its the **Engineering Robot**, and on the right is the **Standard Robot***



#### Functionality and Technical Detail

* **Standard Robot** 

  * You can Build Up to Three
  * **Fully-Autonomous shooting**
  * **Assist maneuvering**
  * It is the flexible robot of all
  * It is the main fire power of the team
  * It can only Launch 17mm projectiles
  * It has 750 HP in the start.
  * If destroyed, can be revived by the Engineer robot

* **Hero Robot** 

  * You can Build Up to One
  * **Fully-Autonomous shooting**
  * **Assist maneuvering**
  * Only 1 Hero Robot is allowed
  * It is the most powerful robot overall
  * It can launch both 17mm and 42 mm pro jectile (10x Damage)
  * It can Land the Resource Island
  * It has an 1500 health point at the start o Revivable by the Engineering Robot

* **Engineering Robot** 

  * You can Build Up to One
  * **Fully-Autonomous shooting**
  * **Assist maneuvering**
  * Only 1 Engineering Robot is allowed
  * It has the highest Health point overall, with 5000 heath point at start
  * It is mainly used to retrieve the higher attack value ammo (42mm) located at the ammo box, thus, usually, some type of grabing mechnisim is needed.
  * It needs to deliver the 42mm ammo to Hero Robot
  * Engineering Robot is the only Robot that can retrive dead robot (Heath point depleted)
  * Can not launch any projectile
  * Revivable by others

* **Sentery Robot** 

  * You can Build Up to One
  * **Fully-Autonomous** **maneuvering**
  * **Fully-Autonomous shooting**
  * Move on a dedicated rail system

* **Aerial Robot** 

  * You can Build Up to One

  * **Fully-Autonomous shooting**

  * **Assist maneuvering**

  * Control by two operator who can not communicate with each other during the game. One is incharge of flying and the other is incharge of shooting and other maneuver

    

## Entire Robot Fleet Price Break Down

<span style="color:red">**What we current need to buy is marked RED**</span> 

What we already have is marked BLACK

* Standard Robot (Total Cost: **$4619**)
  * Mechinical component fabrication and material Cost: **$1500**
  * Custom Electronics and DJI brand motors and ESCs: **$1000**
  * Jetson TX2 Embedded Computer for Computer Vision: **$600**
  * <span style="color:red">Super-Capacitor Bank: **$100**</span> 
  * <span style="color:red">Jetson TX2 Expansion Board: **$300**</span> 
    * This enable us to shrink the TX2's form factor to fit the standard robot chassis.
  * Sensors and Cameras:
    * <span style="color:red">Real Sense Depth Camera: **$200**</span>
    * <span style="color:red">A3 LIDAR system: **$599**</span>
  * Battery x2: **$320**
* Engineering Robot (Total Cost: **$4569**)
  - Mechinical component fabrication and material Cost: **$2000**
  - Custom Electronics and DJI brand motors and ESCs: **$1200**
  - <span style="color:red">Super-Capacitor Bank: **$100**</span> 
  - <span style="color:red">Pneumatic Components: **$350**</span>
    - Contain Pneumatic actuators and carbon fiber high pressure tank
  - <span style="color:red">A3 LIDAR system: **$599**</span>
  - Battery x2: **$320**
* Hero Robot (Total Cost: **$4669**)
  - Mechinical component fabrication and material Cost: **$1550**
  - Custom Electronics and DJI brand motors and ESCs: **$1000**
  - Jetson TX2 Embedded Computer for Computer Vision: **$600**
  - <span style="color:red">Super-Capacitor Bank: **$100**</span> 
  - <span style="color:red">Jetson TX2 Expansion Board: **$300**</span> 
    - This enable us to shrink the TX2's form factor to fit the standard robot chassis.
  - Sensors and Cameras:
    - <span style="color:red">Real Sense Depth Camera: **$200**</span>
    - <span style="color:red">A3 LIDAR system: **$599**</span>
  - <span style="color:red">Battery x2: **$320**</span>
* Sentry Robot (Total Cost: **$3020**)
  - <span style="color:red">Mechinical component fabrication and material Cost: **$900**</span>
  - <span style="color:red">Custom Electronics and DJI brand motors and ESCs: **$700**</span>
  - Jetson TX2 Embedded Computer for Computer Vision: **$600**
  - <span style="color:red">Jetson TX2 Expansion Board: **$300**</span> 
    - This enable us to shrink the TX2's form factor to fit the standard robot chassis.
  - Sensors and Cameras:
    - <span style="color:red">Real Sense Depth Camera: **$200**</span>
  - <span style="color:red">Battery x2: **$320**</span>
* Aerial Robot (Total Cost: **3970**)
  * <span style="color:red">DJI-Matrice 100 Drone **$1650**</span>
  * <span style="color:red">Mechinical component fabrication and material Cost for gimbal and others: **$500**</span>
  * <span style="color:red">Custom Electronics and Gimbal Motos, ESCs: **$400**</span>
  * Jetson TX2 Embedded Computer for Computer Vision: **$600**
  * <span style="color:red">Jetson TX2 Expansion Board: **$300**</span> 
    - This enable us to shrink the TX2's form factor to fit the standard robot chassis.
  * Sensors and Cameras:
    - <span style="color:red">Real Sense Depth Camera: **$200**</span>
  * <span style="color:red">Battery x2: **$320**</span>



## Club Funding

### How much have we raised so far? 

**To date, we have raised around \$15,000,** half of which is from **student's club due** and the other half from **sponsors including John Deere and Andymark**. 

Our current sposonsor include:

* DJI
* John Deere
* PESC
* Purdue University School of Mechnical Engineering
* Purdue University School of Engineering Technology
* AndyMark
* SolidWorks
* Bechtel Innocation and Design Center

For the \$15,000 we have raised so far, **we spent it mostly in the contruction of our 2 standard robot, Hero Robot, and Engineering Robot**. 



### What can we do with more funding?

With an additional $15000-\$20000 in funding, we believe we will be able to purchase the items required to complete the rest of the robot fleet (**Sentry Robot**, **Aerial Robot**, and **one** **more** **Standard Robot**) and **rent space in the Anvil to practice the competition**. Your support will go a long way in helping us to reach our goals, and we will utilize this resource wisely and efficiently. 



#### Robots:

- Standard Robot **Upgrade # 1**(**Still Need:** **$999**) *This robot has already build, but still need upgrade*
  - <span style="color:red">Jetson TX2 Expansion Board: **$300**</span> 
    - This enable us to shrink the TX2's form factor to fit the standard robot chassis.
  - <span style="color:red">Super-Capacitor Bank: **$100**</span> 
  - Sensors and Cameras:
    -  <span style="color:red">A3 LIDAR system: **$599**</span>
- Standard Robot **Upgrade # 2**(**Still Need:** **$999**) *This robot has already build, but still need upgrade*
  - <span style="color:red">Jetson TX2 Expansion Board: **$300**</span> 
    - This enable us to shrink the TX2's form factor to fit the standard robot chassis.
  - <span style="color:red">Super-Capacitor Bank: **$100**</span> 
  - Sensors and Cameras:
    - <span style="color:red">A3 LIDAR system: **$599**</span>
- **Third** Standard Robot (**Still Need:** **$3819**) *This robot has not been build*
  - <span style="color:red">Mechinical component fabrication and material Cost: **$1500**</span> 
  - <span style="color:red">Custom Electronics and DJI brand motors and ESCs: **$1000**</span> 
  - <span style="color:red">Super-Capacitor Bank: **$100**</span> 
  - <span style="color:red">Jetson TX2 Expansion Board: **$300**</span> 
    - This enable us to shrink the TX2's form factor to fit the standard robot chassis.
  - Sensors and Cameras:
    - <span style="color:red">A3 LIDAR system: **$599**</span>
  - <span style="color:red">Battery x2: **$320**</span>
- Engineering Robot (**Still Need**: **$1049**) *This robot has partially build, but still need upgrade*
  - <span style="color:red">Pneumatic Components: **$350**</span>
  - <span style="color:red">Super-Capacitor Bank: **$100**</span> 
    - Contain Pneumatic actuators and carbon fiber high pressure tank
  - <span style="color:red">A3 LIDAR system: **$599**</span>
- Hero Robot (**Total Cost:** **$1319**) *This robot has partially build, but still need upgrade*
  - <span style="color:red">Jetson TX2 Expansion Board: **$300**</span> 
    - This enable us to shrink the TX2's form factor to fit the standard robot chassis.
  - <span style="color:red">Battery x2: **$320**</span>
  - <span style="color:red">Super-Capacitor Bank: **$100**</span> 
  - <span style="color:red">A3 LIDAR system: **$599**</span>
- Sentry Robot (**Total Cost:** **$2520**) *This robot has not been build*
  - <span style="color:red">Mechinical component fabrication and material Cost: **$900**</span>
  - <span style="color:red">Custom Electronics and DJI brand motors and ESCs: **$1000**</span>
  - <span style="color:red">Jetson TX2 Expansion Board: **$300**</span> 
    - This enable us to shrink the TX2's form factor to fit the standard robot chassis.
  - <span style="color:red">Battery x2: **$320**</span>
- Aerial Robot (**Total Cost:** **$2850**) *This robot has not been build*
  - <span style="color:red">DJI-Matrice 100 Drone **$1650** (With 50% DJI Discount)</span>
  - <span style="color:red">Mechinical component fabrication and material Cost for gimbal and others: **$500**</span>
  - <span style="color:red">Custom Electronics and Gimbal Motos, ESCs: **$400**</span>
  - <span style="color:red">Jetson TX2 Expansion Board: **$300**</span> 
    - This enable us to shrink the TX2's form factor to fit the standard robot chassis.

**Total cost to complete our robots: $10,560**

**<u>Total cost to complete robots and begin to implement LIDAR: $13,555</u>**



#### Shipping:

- Method #1 Shipping by **logistic company**: We have also contacted Purdue Shipping and Receiving for assistance.  They suggested having them crated and shipped.  They are working with us to get an ATA form for duty free import/export of temporary items.
  - <span style="color:red">**$5000** </span>Round trip for **3x Standard Robots, Hero Robot, Engineering Robot, Sentry Robot**
  - Pelican Air 1615NF Hard Case **x 8** for **3x Standard Robots, Hero Robot, Engineering Robot, Sentry Robot** = <span style="color:red">**$2120** </span>
- **OR**
- **Preffered** Method #2 Shipping by **checked luggage** 
  - Pelican Air 1615NF Hard Case **x 8** for **3x Standard Robots, Hero Robot, Engineering Robot, Sentry Robot** = <span style="color:red">**$2120** </span> 
  - This is re-useble



<u>**By using the recomended method #2, we need $2120 for the transportation**</u>



#### Testing Feild:

Space Rent = $600/semester at the Anvil (may not be available due to University’s 

acquisition of this space)

Building Materials = $400 – Wood / electronics / fasteners



<u>**Estimate Cost: $1000**</u>



## Funding Priority

* Shipping: $2120
* Finalize Robots without LIDAR: $10,560 (Possibly withou Aerial if short on funds then 7710)
* Testing Field: $1000
* LIDAR upgrade: $2995



## To learn more

Attached are updated **presentation slides** and **research papers**. 

Here is also a **link to our team website** which is very comprehensive and full of illustration and promotion material, **I highly recommend to pay a visit for your information.**



https://purduerm.com/



Much appriciate for you consideration,

**Chengming Zhang** 

*President of the Purdue Robomaster Club*

