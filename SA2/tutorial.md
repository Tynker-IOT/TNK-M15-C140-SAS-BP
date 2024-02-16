Access MQTT data from Node-RED
======================
In this activity, you will access the sensor data from Node-RED using the MQTT broker.








<img src= "https://s3.amazonaws.com/media-p.slid.es/uploads/1525749/images/11089823/SA2.gif" width = "100%" height = "50%">








Follow the given steps to complete this activity.








1. Connect to the MQTT broker.


    * Add two mqttin widgets from the network section.




    <img src= "https://s3.amazonaws.com/media-p.slid.es/uploads/1525749/images/11089630/SA2_1.1_mqttin.gif" width = "80%" height = "50%">


    * Double click on the widgets to add the server and topics `/Temperature` and `Humidity`.


    <img src= "https://s3.amazonaws.com/media-p.slid.es/uploads/1525749/images/11089766/SA2_1.2.gif" width = "80%" height = "50%">


2. Display the payload by adding debug widget and connecting them to the mqttin widget.


    <img src= "https://s3.amazonaws.com/media-p.slid.es/uploads/1525749/images/11089816/SA2_2.gif" width = "80%" height = "50%">


    * Add two debug widgets from the common section.
    * Connect `Temperature` and `Humidity` widgets to the debug widgets.
    * Click on the `Deploy` button.
    * Click on the `Debug` icon to open the debug section.
    * Run the [Wokwi project](https://wokwi.com/projects/386715962692146177)
    * Change the values of the sensor.
    * Observe the reading from the sensors on the debug section.


    <img src= "https://s3.amazonaws.com/media-p.slid.es/uploads/1525749/images/11089823/SA2.gif" width = "80%" height = "50%">
