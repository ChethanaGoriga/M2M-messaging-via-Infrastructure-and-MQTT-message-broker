# M2M-messaging-via-Infrastructure-and-MQTT-message-broker
Created a filter string and initialize it to an empty string.
If the filter string is empty then react to the messages "0" and "1" as in the original program.
If the filter string is not empty then react only to the "0" and "1" messages sent by the machine that has ID equal to that string.
When the button is continuously pressed for one or more seconds then every 0.1 second the board shall be repetitively sending a message with value of "2" instead of "0" OR "1" until the button is released.
When the button is continuously pressed for one seconds then at the exact the one second time reset the filter string.
When the button is continuously pressed for more than one second each time you receive a message of "2" store the sender machine ID in the filter string by overwriting the previous value.
Run "MQTT traffic injector" either on your laptop or on a lab PC, this take care of the third or more ESP boards.
