This aim of the component is to demonstrate attribute passing between 2 components

1) we can use aura:attribute/ aura:method / aura:event to pass attributes between components

aura:attribute and aura:method are used for passing data/message between components inside the same app while event is used when the components do not have visibility to each other

https://salesforce.stackexchange.com/questions/136837/lightning-events-vs-parameters/136863

In general events are bulky and recommended practice is to implement aura:method/attribute when possible.

In this component 

1) comp1 gets the account list as json string 

2) JSON string is passed to the second component 

3) Using JSON.deserealize the account json is converted back into account list to be displayed on component 2 

![screenshot](https://github.com/Rao6308/Passparamsbetweencomponents/blob/master/src/passparamfromcomp1tocomp2.JPG)