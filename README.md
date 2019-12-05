Turns on i2c on a Raspberry Pi and install a docker container for the Adafruit Motor controller and ROS.

# vars

ros_ip: "{{ ansible_ssh_host }}"
ros_master_uri: "http://{{ ansible_ssh_host }}:11311"

cpu_arch: "latest"