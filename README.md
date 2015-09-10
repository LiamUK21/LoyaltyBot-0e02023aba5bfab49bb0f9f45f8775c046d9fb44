# LoyaltyBot-0e02023aba5bfab49bb0f9f45f8775c046d9fb44
var loyaltybot = require('./../lib/initialize.js');

loyaltybot.initialize({
    // twitch info
    twitch : {
        channel     : 'Liam_gunboun',
        bot         : {name: 'Silverwingsbot', password: 'fuckyou11'},
        subscribers : 'https://spreadsheets.google.com/feeds/list/****/od6/public/basic?alt=json'
    },

    // currency info
    currency : {
        name     : 'Silverwings',
        payrate  : 5,
        host     : '127.0.0.1',
        user     : 'mysql_user',
        password : 'mysql_password',
        database : 'mysql_database',
        website  : 'http://www.loyaltypoints.com'
    },

    // optional features
    commands: true
});
