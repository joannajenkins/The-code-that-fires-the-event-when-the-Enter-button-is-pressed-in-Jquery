# The-code-that-fires-the-event-when-the-Enter-button-is-pressed-in-Jquery
The code that fires the event when the Enter button is pressed in Jquery
$(".input1").on('keyup', function (e) {
    if (e.keyCode === 13) {
        // Do something
    }
});
