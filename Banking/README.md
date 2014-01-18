What does this print?

    var stockOptionsCost = 10.70,
        paid = 20.80;

    function calculateChange() {

        return paid - stockOptionsCost;
    }

    function calculateAmountOfStockOptions () {
        return paid / stockOptionsCost;
    }

    console.log( 'You purchased ' + calculateAmountOfStockOptions() + ' Stock Options.' )
    console.log( 'Take your change [' + calculateChange()  + '] and thanks for buying with Bank Ruptcy' );

Why?

How could you fix it?
