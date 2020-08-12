error: 
javax.el.PropertyNotFoundException: /add.xhtml @55,104 value="#{prperty.streetAddress}": Target Unreachable, identifier 'prperty' resolved to null
reason: the name has error("property" rather than "prperty" in this case)
modify it directly

other reason: 
1. The first letter of the the getter/setter method name should be lowercase;
2. cannot load the xml file of bean 
(<import resource="com/user/info/bean/configure/application-user-beans.xml" />)

