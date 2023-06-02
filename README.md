# Energy Efficient Path Planning for Aerial Photography Based Disaster Response
The unmanned aerial vehicle (UAV) is often used in disaster management. For example,
after a disaster, people can use the UAV to detect the disaster area to find the damaged buildings
and residents; and in the disaster recovery stage, the UAV can be used to assess the severity of
the disaster, the feasibility, and cost of the reconstruction. They are utilised to assist people in
disaster reconstruction planning. However, a serious problem with UAV is that their battery is
limited and cannot be used for long-term or large-scale survey tasks. Therefore, how to develop a
feasible flight path for efficient and accurate target detection has become a very important issue.
This task mainly consists of an important aspect of energy aware path planning.

![image](https://github.com/agpiyush101/Energy_Aware_Path_Planning/assets/85208950/8236fabe-3b9a-4fd3-8749-6e3e18c86d53)

# PATH PLANNING
When we talk about the energy efficient path planning algorithm, the first thing we can
consider for the path planning is that the distance travelled by the UAV should be minimum and
second thing we can consider is to minimise the number of turns as the figures given below
figure a has more number of turns as compared to figure b. So the second path planning would
be better.

![image](https://github.com/agpiyush101/Energy_Aware_Path_Planning/assets/85208950/51496964-f7c0-44bf-a024-9fb57b7d209e)

# PLUTO 1.2
Pluto aims at providing an ultimate user experience in terms of flight experience as well
as tinkering. We believe that tinkerers have great ideas. Some of which can even change the
world. PlutoX is a great prototyping tool for implementing our ideas. Tinkering is an interesting
hobby and the development tool plays a very important role in making it an engrossing
experience. A basic development tool will provide a platform where the tinkerer has to begin
from scratch every time and gradually start implementing their ideas, which surely is time
consuming. However, if a development tool provides an effortless platform for the tinkerers to
directly develop their ideas on, without the need of worrying about the rest of the system, it will
definitely be more productive. With this perspective, we do not want our tinkerers to waste their
energy in figuring out how to get the drone to fly but to focus only on what they want to do and
achieve with the drone . For this purpose, we have done all the work required for Pluto to fly and
hence, tinkerers do not need to worry about that. Even without any tinkering, a user can easily fly
Pluto. The entire system has been designed in such an elegant way that the tinkerers can directly
start implementing their ideas by coding into the platform provided to them.

## Hardware
![image](https://github.com/agpiyush101/Energy_Aware_Path_Planning/assets/85208950/1c16c907-42ea-43ee-847d-259278cc748b)

## Software
### Workig of the software
![image](https://github.com/agpiyush101/Energy_Aware_Path_Planning/assets/85208950/d04b424a-103a-4144-af46-64b84b5dab0f)

### Control Block
Control Block, as the name suggests, controls the movement of the drone across
all the axes, both translational and rotational. This is achieved by using PIDs. This block receives
input data from Estimate Block and from User Block. The Estimate Block provides the current
values of the state variables of PlutoX. The User Block provides the desired values of the state
variables as received from the user.

![image](https://github.com/agpiyush101/Energy_Aware_Path_Planning/assets/85208950/d2aaa76d-f29d-48d4-aaae-93291fe30f62)

# Energy Model

## Mathematical Model
![image](https://github.com/agpiyush101/Energy_Aware_Path_Planning/assets/85208950/e5e1a0a7-945a-4a01-8fc9-e6d220e9350d)

## Li-Po Battery Energy Model
![image](https://github.com/agpiyush101/Energy_Aware_Path_Planning/assets/85208950/41040330-bc75-4101-8bf3-58f1c1d10d67)
![image](https://github.com/agpiyush101/Energy_Aware_Path_Planning/assets/85208950/7cbe7989-6dc6-4b9b-9542-385f4c5d7462)
The Lipo battery of 600mAh and 1C is used for flying the drone.So for the calculation of
energy consumed for per 0.1 V drop the Lipo battery discharge curve is as following




