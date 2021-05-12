# Vue.js 2 Lifecycle hooks

# beforeCreate() : 
    This method is called synchronously after the Vue instance has just been initialized, before data observation and event/watcher setup.

# created() : 
    This method is called synchronously after the Vue instance is created. Data observation, computed properties, methods and event callbacks have already been set up at this stage but the mounting phase has not started yet.

# beforeMount() : 
    This method is called right before the component is mounted. So it is called before the render method is executed.

# mounted() : 
    This method is called after the component has just been mounted.

# beforeUpdate() : 
    This method is called when the data changes, before the virtual DOM is re-rendered and patched.

# updated() : 
    This method is called after a data change causes the virtual DOM to be re-rendered and patched.

# activated() : 
    This method is called when a kept-alive component is activated.

# deactivated() : 
    This method is called when a kept-alive component is deactivated.

# beforeDestroy() : 
    This method is called right before a Vue instance or component is destroyed. At this stage the instance is still fully functional.

# destroyed() : 
    This method is called after a Vue instance or component has been destroyed. When this hook is called, all directives of the Vue instance have been unbound, all event listeners have been removed, and all child Vue instances have also been destroyed.


Refer Images: https://camo.githubusercontent.com/77db71e72a5beef799117ec19e98ecb513482265a9c5854fd33b5c65307e8d1a/68747470733a2f2f7675656a732e6f72672f696d616765732f6c6966656379636c652e706e67