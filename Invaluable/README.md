What does this print?

    var strMethod = 'valueOf',
        strProperty = 'length',
        value = [44 + 22][strMethod]()[strProperty];

	console.log( value );

	value = [44 + 22][strMethod][strProperty];

	console.log( value );

Why?