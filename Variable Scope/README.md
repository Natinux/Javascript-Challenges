What does this print?

    var name = 'John',
        obj = {
            name: 'Mary',
            whoIam: function() {
                var name = 'James';

                console.log( this.name );       // a)

                setTimeout( function () {
                    console.log( this.name );   // b)
                }, 100 );
            }
        };

    obj.whoIam();

Why?