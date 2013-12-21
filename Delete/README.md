What does this print?

    var name = 'John',
        obj = {
            name: 'James'
        },
        Animal,
        mammal;

    Animal = function(){};
    Animal.prototype.name = 'animal';

    mammal = new Animal();

    delete name;

    console.log(name);

    delete obj.name;

    console.log(obj.name);

    delete obj.toString;

    console.log(obj.toString);

    delete mammal.name;

    console.log(mammal.name);

Why?