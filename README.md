# el_hourri_bihlal_delete_client
this is the service in charge of deleting a client by providing his id
example to run the program and delete the clientId 5 in spark master virtual machine (please refer to the attachement below to have a view of the network architecture): 
 cmd command:
 ./spark-submit --packages "com.github.scopt:scopt_2.12:4.1.0" --class deleteApp --master spark://172.31.249.172:7077 /home/nodekamicode/deleteApp/target/scala-2.12/deleteapp_2.12-1.0.jar -i 5
