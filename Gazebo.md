<h2> Cost-effectiveness of ROS Gazebo</h2>
This study evaluates the cost-effectiveness of an open source UAS simulator known as Robotic Operating System (ROS) Gazebo (Koenig & Howard, 2004). In this case study, the evaluation of ROS Gazebo will consider the time and expenses required to design UAS prototypes by comparing the cost with and without simulation, within the regulations of Singapore. The main purpose of simulation is to bridge virtual and actual performance by providing realistic conditions and feedback during simulation to enable positive transfer as well as modeling of flight conditions (Vincenzi, 2009). Further, simulation systems could be regarded as cost-efficient in terms of (1) time and (2) expenses to achieve intended outcomes (Vincenzi, 2009). 

<h3>Background</h3>
The UAS community of Singapore recently held a series of engagements on Advanced Air Mobility (AAM), featuring urban air mobility vehicles, UAS use cases, regulatory oversight, and challenges (Association of Aerospace Industries (Singapore) (AAIS), 2020a). Meanwhile, the Federal Aviation Administration (FAA) published airworthiness criteria for various drone operations applicants such as Amazon and Zipline, whose “complex drone operations” are allowed under the sUAS rule (Part 107) given regulatory conditions such as lightning protection, software and testing (FAA, 2020). These FAA registers served as references for development for the local community (AAIS, 2020). For localized and international market entry as well as research and development, individuals and companies require cost-effective and sustainable means of simulation and testing for UAS.

<h3>Simulator Selection</h3>
For UAS design simulation software, the requirements depend on the design phase, required fidelity of aerodynamics and sensor availability as well as performance (Vogeltanz, 2016). Researchers have previously designed a UAS prototyping simulation application using ROS Gazebo and COTS modules for an indoor simultaneous localization and mapping (SLAM) task with an accuracy of ±0.5m in terms of path planning and execution (Zhang et al., 2015). While the researchers suggested that the results were acceptable, cost-effectiveness was not evaluated, which could improve the practicality and validity of their research. 

<h3>Engineering Duration and Regulatory Cost</h3>
It is assumed that a junior robotics engineer can complete the setup of Gazebo and UAS prototype within a month while conducting field trials within the subsequent month, at a monthly salary of $3,500. Compared to actual flights of UAS prototypes, UAS simulation allows enthusiasts, commercial operators and academics to trim down or defer initial prototyping costs by a sizeable factor of $3,000 due to delayed ab-initio UAS pilot training as well as operator and activity permits for heavier UAS shown below (CAAS, n.d.-a, n.d.-b, 2020a, 2020b). 



<img src="https://github.com/liauwkw/ASCI638/blob/main/UAS%20regulatory%20cost.png" width="100%" style="max-width:100%;">

<h3>Hardware Cost</h3>
In terms of hardware, a sample of components amounting to $850 could produce an AI-capable SLAM UAS as shown in the table below. This cost must be offset with those of the simulation system which costs less at $810 inclusive of accessories at present local prices for used-components to build a Linux operating system running on Intel I5-equivalent CPU, 500MB disk space with a dedicated GPU. While the asset costs are comparable, the hallmark of computer simulation systems is the savings on recurrent costs of the same, hence users could expect to avoid additional costs of up to $854 per iteration or replacement of UAS. 

<img src="https://github.com/liauwkw/ASCI638/blob/main/BOM6.png" width="90%" style="max-width:90%;">

<h3>Evaluation of Cost-effectiveness</h3>
Within a two-month prototyping period comprising separate lab and field trials, the use of simulation is cost-effective for the first month due to the deferment of regulatory costs, which would be applied if the prototype proceeds from the lab to field trial as follow:

<img src="https://github.com/liauwkw/ASCI638/blob/main/costeffectivenesseval4.png" width="100%" style="max-width:100%;">

<h3>Limitations of Evaluation</h3>
Thus far, the time and expenses method did not consider the value proposition of expertise, innovation, research capabilities and knowledge management, which are advantageous in research and development of UAS. Reviewing past implementations of various simulations in the military context, researchers further elaborated that there are process innovation benefits to be considered, such as safer and quicker processes when incorporated into “System Acquisition” (Vincenzi, 2009, p. 12). These factors present a broad definition encompassing opportunity costs as well as the transfer of training, while making commercial Return on Investment (ROI) calculations presented earlier seem brief (Bonnabry & François, 2020). Hence, the development of an organization-specific evaluation of cost-effectiveness could be beneficial.

<h3>Conclusion</h3>
	In summary, the use of a UAS simulator based on open source software presents a gradual onset of costs. Further, the simulator defers initial costs with only marginal savings on total cost. The key benefit of using an open-source UAS simulation tool as compared to building an actual prototype is the reduction of losses in event of failure, as well as the potential reduction of iteration costs due to the use of computer simulation. Further studies could be performed on the fidelity and viability of ROS Gazebo simulation for outdoor environments.

<h4>@liauwkw, 2020</h4>

<h3>References</h3>

Association of Aerospace Industries (Singapore) (AAIS). (2020a). AAM Webinar Series 1: Singapore and Advanced Air Mobility. Retrieved from https://aais.org.sg/aam1/

Association of Aerospace Industries (Singapore) (AAIS). (2020b). Singapore UAS Community. Retrieved November 29, 2020, from LinkedIn website: https://www.linkedin.com/posts/sg-uas_faa-moving-forward-to-enable-safe-integration-activity-6737518071331864576-KXqH

Avetics Pte Ltd. (n.d.). UATO Course 2B - Theory + Practical + Test ≤ 25kg. Retrieved November 29, 2020, from https://uato.avetics.com/courses/UATO-course-2b

Bonnabry, P., & François, O. (2020). Return on investment: A practical calculation tool to convince your institution. European Journal of Hospital Pharmacy , 27(2), 111–113. https://doi.org/10.1136/ejhpharm-2018-001733

Civil Aviation Authority of Singapore (CAAS). (n.d.-a). UA Operator and Activity Permits. Retrieved October 5, 2020, from CAAS website: https://www.caas.gov.sg/public-passengers/unmanned-aircraft/ua-regulatory-requirements/ua-operator-and-activity-permits

Civil Aviation Authority of Singapore (CAAS). (n.d.-b). UA Pilot Licence. Retrieved November 27, 2020, from UA Regulatory Requirements website: https://www.caas.gov.sg/public-passengers/unmanned-aircraft/ua-regulatory-requirements/ua-pilot-licence

Civil Aviation Authority of Singapore (CAAS). (2020a). Permits for Unmanned Aircraft Operations. Advisory Circular, AC 101-2-1(August). Retrieved from https://www.caas.gov.sg/docs/default-source/docs---spp/ac-anr101-2-1(1)-permits-for-ua-operations-18aug20-(1).pdf

Civil Aviation Authority of Singapore (CAAS). (2020b). Unmanned Aircraft Pilot Licence (UAPL). Advisory Circular, AC 101-4-1(July). Retrieved from https://www.caas.gov.sg/docs/default-source/docs---spp/ac-101-4-1-r(0)-uapl.pdf

Federal Aviation Administration (FAA). (2020). FAA Moving Forward to Enable Safe Integration of Drones. Retrieved November 29, 2020, from News & Updates website: https://www.faa.gov/news/updates/?newsId=96138

Koenig, N., & Howard, A. (2004). Design and use paradigms for Gazebo, an open-source multi-robot simulator. 2004 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), 3, 2149–2154. https://doi.org/10.1109/iros.2004.1389727

Vincenzi, D. A. (Ed.). (2009). Human factors in simulation and training. 

Vogeltanz, T. (2016). A Survey of Free Software for the Design, Analysis, Modelling, and Simulation of an Unmanned Aerial Vehicle. Archives of Computational Methods in Engineering, 23(3), 449–514. https://doi.org/http://dx.doi.org/10.1007/s11831-015-9147-y

Zhang, M., Qin, H., Lan, M., Lin, J., Wang, S., Liu, K., … Chen, B. M. (2015). A high fidelity simulator for a quadrotor UAV using ROS and Gazebo. IECON 2015 - 41st Annual Conference of the IEEE Industrial Electronics Society, 2846–2851. https://doi.org/10.1109/IECON.2015.7392534


