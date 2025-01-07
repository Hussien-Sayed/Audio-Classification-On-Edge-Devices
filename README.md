# Audio-Classification-On-Edge-Devices

TechCabal is a leading technology publication and event organizer dedicated to showcasing the transformative impact of technology in Africa. Umbaji, an AI startup specializing in developing custom AI datasets and models, partnered with TechCabal for this project. Umbaji has a proven track record of creating tailored AI solutions, such as speech-to-text systems, and works closely with local startups to address unique challenges in underrepresented regions. 

The purpose of this project is to develop a lightweight, resource-efficient machine learning model that's capable of recognizing basic directional commands in Ewe, a West African language. The task is to build a model that accurately classify audio recordings of eight directional words ("up," "down," "stop," "go," "left," "right," "yes," and "no"). Key constraints ensured models could operate on edge devices with limited resources, emphasizing real-world usability. The project not only addresses a critical accessibility need but also highlights the potential of AI in supporting underrepresented languages and communities.

The model was tested succesfully on a single CPU ARM Cortex-A55 and has a less than 50ms inference time using an android device. To meet the small size constraint, A new variant small architecture of ResNet is introduced to model the problem.
