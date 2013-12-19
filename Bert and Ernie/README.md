What does this print?

    var bird = 'Pidgeons';
    ( function () {
        if ( typeof bird === 'undefined' ){
            var bird = 'Rubber Duck';
            console.log('Ernie loves his ' + bird );
        } else {
            console.log('Bert loves his ' + bird );
        }
    }() );

Why?

How could you fix it?