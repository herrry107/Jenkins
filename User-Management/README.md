# User Management

**Create User**

Go to **"Jenkins Dashboard -> Manage Jenkins -> Users"**

![Users](https://github.com/herrry107/Jenkins/blob/main/images/user-management/jenkins-user.png)

Create User with name of varun **"Jenkins Dashboard -> Manage Jenkins -> Users -> Create User"**

![Create User](https://github.com/herrry107/Jenkins/blob/main/images/user-management/jenkins-user-create.png)

Now login with user varun and you will see varun user have all rights all permission like admin

# Role-Based Authorization Strategy

Now we have option of **"Role-Based Strategy"**

Go to manage jenkins -> plugins -> available plugins -> Role-Based Authorization Strategy -> install without restart

![Role-Based Authorization Strategy](https://github.com/herrry107/Jenkins/blob/main/images/user-management/jenkins-user-role-based-plugin.png)

Now again try to login with user varun and you will see the message ***"varun is missing the overall/Read permission"***

For provide user to access/permission we have to attach roles.

**1) firstly enable role based strategy into authorization**

Go to **Manage Jenkins -> Security -> Authorization -> Role-Based Strategy**

![Security](https://github.com/herrry107/Jenkins/blob/main/images/user-management/jenkins-user-role-based-1.png)

![Role-Based Strategy](https://github.com/herrry107/Jenkins/blob/main/images/user-management/jenkins-user-role-based-2.png)

