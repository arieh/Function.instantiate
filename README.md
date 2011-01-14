Function.instantiate
================
Function.instantiate allows you to pass dynamically created arguments list to the new operator. 

How to use
----------

You can use the method in 2 ways:

    #JS
    var fx = Function.instantiate(Fx.Morph,[$('el')]);
   
    var fx = Fx.Morph.instantiate([$('el')]);
    
