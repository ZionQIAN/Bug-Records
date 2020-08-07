error decription:
server error: ... Target Unreachable, 'null' returned null
it presents that

value="#{userController.users.username}": 
Target Unreachable, 'null' returned null

Either #{userController} or #{userController.users} is null

need a constructor
for example: 

public void init() {
    users = new Iuser();
}