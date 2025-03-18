!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CPA Offers | High-Converting Landing Page</title>
    <link rel="stylesheet" href="styles.css">
    
    <!-- CPAGrip Content Locker Script -->
    <script type="text/javascript" src="https://rockingfolders.com/show.php?l=0&u=859453&id=68658"></script>
    
    <!-- Additional Script (Replace with actual script URL or content) -->
    <script type="text/javascript" src="https://rockingfolders.com/show.php?l=0&u=859453&id=67671"></script>
    
    <style>
        /* Existing styles */
        footer {
            background: #333;
            color: #fff;
            padding: 10px;
            position: relative; /* Changed from fixed to relative */
            left: 0; /* Ensure it spans the full width */
            right: 0; /* Ensure it spans the full width */
            bottom: 0; /* Removed to avoid fixed positioning */
        }
    </style>
</head>
<body>
    <header>
        <h1>Exclusive CPA Offers</h1>
        <p>Earn Money Online with High-Paying Offers</p>
    </header>
    
    <section class="offer-container">
        <div class="offer-card">
            <div id="toast" style="display:none; position:fixed; bottom:20px; left:50%; transform:translateX(-50%); background-color:#333; color:white; padding:10px; border-radius:5px;">
                Offer unlocked!
            </div>
            <h2>Get a $500 Gift Card!</h2>
            <p>Sign up and complete a simple survey to claim your reward.</p>
            <a href="#" class="cta-button" data-offer="Get a $500 Gift Card!">Unlock Offer</a>
        </div>
        
        <div class="offer-card">
            <h2>Win a $500 Kohl's Gift Card!</h2>
            <p>Enter your email and stand a chance to win.</p>
            <a href="#" class="cta-button" data-offer="Win a $500 Kohl's Gift Card!">Unlock Offer</a>
        </div>
    </section>
    
    <footer>
        <p>&copy; 2025 CPA Offers. All rights reserved.</p>
    </footer>
    
    <script>
        document.addEventListener('DOMContentLoaded', function() {
            document.querySelectorAll('.cta-button').forEach(button => {
                button.addEventListener('click', function(event) {
                    event.preventDefault();
                    unlockOffer(this.getAttribute('data-offer'));
                });
            });
        });

        function unlockOffer(offer) {
            // Display the toast message
            const toast = document.getElementById('toast');
            toast.style.display = 'block';
            
            // Redirect to a confirmation page after the toast has been displayed
            setTimeout(function() {
                window.location.href = "confirmation.html"; // Example redirect
            }, 8000); // Redirect after 8 seconds to allow for toast visibility
        }
    </script>
</body>
</html>
