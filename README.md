## To Do List

To do list with the ability to display, create, edit and delete your tasks.Also create custom lists and give them the name you want.Task list, to-do list,shopping list and more.
Keep tracking your daily duties and save them on your device.

Application user adds or removes tasks on database,Mongodb, using NodeJs server.

In this project Mongodb doesn't run locally,instead i have deployed it on Mongodb Atlas to make it run on cloud server.
This way we are implementing SAAS model,as db is hosted in cloud and not locally.
(SAAS/db hosted in cloud)

I created a MongoDB cluster(3-shard/node replica set on which DB is hosted) on AWS cloud provider.This way all database updates/maintenance will be done by vendor(AWS).

Through vendor i'm able to check and monitor traffic in cluster,watch new database entries and edit them.

## Stack
+ NodeJs
+ Express
+ Mongodb
+ AWS
+ SAAS