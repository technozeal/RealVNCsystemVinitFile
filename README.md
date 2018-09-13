# RealVNCsystemVinitFile
We encounter problem when installing RealVNC server on MX Linux
In MX Linux, systemd was installed by disabled
When installing RealVNC server, the software detects systemd and configure the software services in systemd file
However, MX Linux uses init.d
It is impossible to force the software to generate init.d file without breaking it
We manage to force the software to reconfigre the services using init.d file
You can download these files into /etc/init.d folder
