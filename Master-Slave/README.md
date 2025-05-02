# Master-Slave

There are 1 master and can be many slave and every slave have different directory.

If we don't specify job to any slave or master that is can go to anyone but we can schedule it who will do it.

# Create Nodes or Slave

**Manage Jenkins -> Nodes**

![Nodes](https://github.com/herrry107/Jenkins/blob/main/images/master-slave/jenkins-nodes.png)

**Manage Jenkins -> Nodes -> New Node**

![New Node](https://github.com/herrry107/Jenkins/blob/main/images/master-slave/jenkins-nodes-new.png)

**Manage Jenkins -> Nodes -> New Node -> Permanent Link**

Give name to slave and tick permanent link

![Permanent Link](https://github.com/herrry107/Jenkins/blob/main/images/master-slave/jenkins-nodes-1.png)

Now Give remote directory path and lauch method
**"Remote root directory"**: /home/pratik/node1-jenkins

**"Launch method"**: Launch agent by connecting it to the controller

![Permanent Link](https://github.com/herrry107/Jenkins/blob/main/images/master-slave/jenkins-nodes-2.png)

Now node(slave is created) but it show cross option now click on it, it will show some command for connecting

![Permanent Link](https://github.com/herrry107/Jenkins/blob/main/images/master-slave/jenkins-nodes-3.png)

Now our slave is connected

![Permanent Link](https://github.com/herrry107/Jenkins/blob/main/images/master-slave/jenkins-nodes-4.png)

Now create label for slave go to **Manage Jenkins -> Nodes -> Setting**

![Permanent Link](https://github.com/herrry107/Jenkins/blob/main/images/master-slave/jenkins-nodes-5.png)

create label for slave go to **Manage Jenkins -> Nodes -> Setting -> Labela**

![Permanent Link](https://github.com/herrry107/Jenkins/blob/main/images/master-slave/jenkins-nodes-6.png)

Now go to project and assign specific slave to run this project click on project configure

![Permanent Link](https://github.com/herrry107/Jenkins/blob/main/images/master-slave/jenkins-nodes-7.png)

click on **"Restrict where this project can be run -> Label Expression"** and type slave label here

![Permanent Link](https://github.com/herrry107/Jenkins/blob/main/images/master-slave/jenkins-nodes-8.png)

now run the project it will run only given slave.
