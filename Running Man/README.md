What does this print?

    var endTheGame = 9007199254740992,
        startTheGame = endTheGame - 100,
        count = 0,
        index;

    for ( index = startTheGame; index <= endTheGame; index++ ) {
        count++;
    }

    console.log(count);

Why?

How could you fix it?