# Synapse Nashorn Class Mediator

Sample class mediator invocation through a synapse config as follows

```xml
<class name="org.wso2.carbon.mediation.mediator.sample.NashornMediator">
    <property name="script" value="var t = {'response': 125};
                                   t.response = mc.getProperty('count');
                                   mc.setPayloadJSON(t);    
                                   "/>
</class>
```

