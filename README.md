
Knowledge of semaphores and synchronisation is required


Semaphore are kernel resources that provide synchronization(techniques used when two threads are executing a "critical section" and want to avoid racing).

![myimage-alt-tag](https://github.com/shaleenarora4/Resource_Allocator/blob/master/draw.png)


Problem Statement 

There are two primary participants; One Teacher(T) and three students(S1,S2 and S3). A student needs four resources to complete a drawing: pencil,paper,sharpener and eraser.Initially, S1 is issued a paper,sharpener and eraser. S2 is issued paper,pencil and eraser. S3 is issued paper,eraser and pencil.Teacher puts any one of the three resources(pencil,eraser and sharpener) on a table and all three students try to take that resource. Only one student will be able to complete the drawing. Teacher keeps repeating the process until all of the students completed their drawing operation.
