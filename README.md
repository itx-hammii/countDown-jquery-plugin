# countDown-jquery-plugin
Jquery plugin for countdown timer. When time reaches to zero it calls a callback function that contains the logic that should run

` $("#countDown").countdownTimer({
        time: 10,
        callback: function () {
          alert("Time's up!");
        },
      });`
this is how you can initialize the plugin. you should be able to change the time and write your own logic in the callback function      
