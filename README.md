# What I Learned in Week 10

### Objects

1. Objects can contain one or more key-values (in pairs)
2. The key is any string.
3. The value property is - function, number, string, array, object.
4. When the value is a function, it is called a method of object.

Example: with function as value

const theObject = {
        greeting : function() {                                                         
                console.log('hey');                                                     
        }                                                                               
        let name : 'Christopher'                                                        
}                                                                                       
theObject.greeting(); will be hi                                                        
console.log(theObject.name); Christopher

You should use object literals for organizing. 