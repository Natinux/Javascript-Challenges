What does this print?

    (function() {
        var values = [3, 8, '15', Math.MAX_VALUE, Infinity, -23],
            oddValues = [],
            index,
            lenValues = values.length,
            isOdd = function ( value ) {
                return value % 2 != 0;
            };

        while(lenValues--) {
            if ( isOdd( values[lenValues] ) ) {
                if(typeof values[lenValues] === 'undefined')
                 {
                 debugger;
                 }
                oddValues.push( values[lenValues] );
            }
        }
        console.log( oddValues );
    }());

Why?