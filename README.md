# victoooorv.github.io
Real Time Systems - Application 6 Website


Example Defense Company is working on a brand new Underwater Pressurized Vessel. They want the vessel to be able to detect the current barometric pressure placed on its hull, and relay that to a web server. They also want it to detect the ambient light surrounding it to know if the visibility is well. This project is design to simulate a real-time embedded system, functioning on FreeRTOS, that serves as a proof of concept for this underwater vessel. it leverages the BMP180 barometric pressure sensor, a lux sensor (photoresistor), 4 status indicator LEDs, and an emergency recall button.

The idea of the project is to test concurrency, seeing that all tasks are functioning properly and within specific real-time deadlines. The timing is predictable, and can be analyzed. The project also takes care to protect shared resources, using binary semaphores, mutexes, and queues, to ensure that race conditions do not happen within the system.
