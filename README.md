# Tutorial
 ## Adding UT Lexus car to prebuilt Carla
- Download the [carla_lexus-0.9.15.tar.gz](https://github.com/UT-ADL/carla_lexus/archive/refs/tags/0.9.15.tar.gz) car.
- Copy carla_lexus-0.9.15.tar.gz inside the import folder under Carla's ROOT directory.
- Run ./ImportAssets.sh from the ROOT directory.
- You can now delete the carla_lexus-0.9.15.tar.gz file from the import folder.
 ## Running UT Lexus car with traffic on prebuilt Carla
From the ROOT directory run:
- ./CarlaUE4.sh
  
From the ROOT/PythonAPI run:
- python generate_traffic.py
- python manual_control.py --filter utlexus
 ## Using Tartu demo track with Carla
You might also want to check out the [Tartu demo](https://github.com/UT-ADL/carla_tartu_demo.git) track from UT-ADL.
