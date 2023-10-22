<!-- Modify this according to your requirement -->
<h3>
Bypassing =>CHECKPOINT 2<= in <span id="countdown">10</span> seconds
</h3>
<!-- JavaScript part -->
<script type="text/javascript">

// Total seconds to wait
var seconds = 10;

function countdown() {
    seconds = seconds - 1;
    if (seconds < 0) {
        // Chnage your redirection link here
        window.location = "https://fluxteam.net/windows/checkpoint/check2.php";
    } else {
        // Update remaining seconds
        document.getElementById("countdown").innerHTML = seconds;
        // Count down using javascript
        window.setTimeout("countdown()", 1000);
    }
}

// Run countdown function
countdown();

</script>
