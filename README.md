# Zabbix template for optical interfaces on a dell switch
[Link to project page](https://github.com/Benjamin-Italiaander/zabbix_dell_optical_interfaces)

Dell Optical interface discovery

This template discovers all optical interfaces and adds them to your host items.

- The actual optical receive power in dBm
- The actual optical transmit power in dBm
- The actual voltage of the interface im mA
- The actual current of the interface in Volt
- The actual temperature of the interface in celcius degree

By default it does a query every 15 min. You can change the interval time by changing the macro value {$OPTICALUPDATEINTERVAL}


I did build and test this template on a Dell Z9100-ON switch.

The oid's i Used i found at:
[here](http://www.circitor.fr/Mibs/Html/D/DELL-NETWORKING-IF-EXTENSION-MIB.php#DellNetIfTransceiverDataEntry)

and
[here](https://mibs.observium.org/mib/DELL-NETWORKING-IF-EXTENSION-MIB/#dellNetIfTransVoltage)



