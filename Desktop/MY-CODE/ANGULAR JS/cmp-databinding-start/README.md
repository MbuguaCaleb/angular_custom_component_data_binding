**TASK**

```
Passing data between our Components.

By default properties are only accessible/bindable from within their
components and so that we can bind data from parent component A to child B

We must us the input decator that allows the property to be implicitly accessible
from other components.

@Input() element:{type:string,name:string,content:string}

element property in this case is now accessible to other components.And since its an object
it may be able to receive .

Input is what makes an elements component property bindable from outside of the component(Parent component).

We may therefore as well bind to Components.
```

**ALIAS**

```
You may assign a component property with a different name via an alias.

@Input('srvElement')  element:{ type: string, name: string,  content: string};

srvElement now beacomes the name of the element property being binded to

```

**Passing Data from Child to Parent Component**

```
Its very similar to event binding.
as from parent to child was similar to property binding.



```

**TIP**

```
Assignment is after an equals sign.

colon is declararing the typescript type.
```

**Notes By**

```
Mbugua Caleb

```
