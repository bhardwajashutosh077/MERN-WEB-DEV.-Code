<html>
    <head>
        <style>
            h1{
                color: rgb(99, 95, 93);
                text-align: center;
                text-decoration: underline;
            }
            body{
                background-color: cornsilk;
                

            }
            marquee{
                text-decoration: underline;
            }
            
            
        </style>
        
        
        
        

    </head>
    <body>
        <h1>Welcome to Live HTML Interpreter.....</h1>
        <marquee>For More Update Allow Notifications</marquee>
        <pre>





        </pre>
        Enter Your Code::<textarea id = "d2" onkeyup="lw()"></textarea>
        <pre>     
                
                
             
        </pre>



        <P>Here is Your Output:</P><div id = "d1"></div><br/>
        <pre>





        </pre>
        <table border="8" width = "100%" , align="Centre">
        <tr>
            <th >About us</th>
            <th>Contact us</th>
            <th>Blogs</th>
            <th>Enquiry</th>
        </tr>
        </table>




        <script>
            function lw(){
                x = document.getElementById("d1");
                y = document.getElementById("d2");
                x.innerHTML = y.value;

        
        
            }
        </script>
        
        
    </body>
</html>
