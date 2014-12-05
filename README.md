>CUDA-CNN
>========



>Functions
>--------
>CNN accelerated by cuda. Test on mnist and finilly get 99.7%

***



>Feature
>--------
>1. Use ***DropConnnect*** to train the NetWork
>2. Support checkpoint, the program will save the best test result and save the network weight in the file "net.txt", If the program exit accidentally, you can continue the program form this checkpoint.
>3. Translate the data set of mnist, including scale, rotate, ***distortion***.
>4.

***

>Compile
>-------
>Depend on opencv and cuda  
>You can compile the code on windows or linux.
>
###Windows
>1. Install vs2010.
>2. Download and install <a href="http://sourceforge.net/projects/opencvlibrary/files/opencv-win/3.0.0-beta/" title="opencv-2.4"> opencv-2.4</a> or other higher versions
>3. Download and install <a href="https://developer.nvidia.com/cuda-downloads", title="cuda-5.0"> cuda-5.0</a> or other higher versions
>4. When you create a new project using VS2010, You can find NVIDIA-CUDA project template, create a cuda-project.
>5. Add the opencv "include path" and "lib path" to the project
>6. Our project use ***cublas.lib*** and ***curand.lib*** from cuda, so the project's link list should include these libs
>
###Linux
>1. Install opencv and cuda
>2. Start the ***nsight*** from cuda
>3. Add the opencv "include path" and "lib path" to the project
>4. Link list should include ***cublas.lib*** and ***curand.lib***

>Informations
>------------
>Author :zhxfl  
>mail   :zhxfl@mail.ustc.edu.cn  
>Welcome for any suggest!!   

