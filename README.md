!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" 
        content="width=device-width, initial-scale=1.0">
        <title> I LOVE YOU</title>
        <style>
            body{
                display: flex;
                justify-content: center;
                align-items: center;
                height: 100vh;
                background-color: aquamarine;
                margin: 0;
                font-family: Arial, Helvetica, sans-serif;
            }
            .message{
                font-size: 2em;
                color: black;
                position: relative;
                animation: fadeIn 2s ease-in-out forwards, moveUp 2s ease-in-out forwards;
            }
           @keyframes fadeIn{
            to{
                opacity: 1;
            }
        }
            @keyframes moveUp {
                to{
                    transform: translateY(-20px);
                }
                
            }
           
        </style>
    </head>
    <div class="message">I LOVE YOU
    </div>
</html>
