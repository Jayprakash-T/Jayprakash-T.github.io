
<html>
   
    <head>
        <title> Hello </title>
       
       <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">
        <script src="https://cdn.jsdelivr.net/npm/vue@2.7.13/dist/vue.js"></script>
        
    </head>
    <body>
        <div class="container">
            <h1>"Using Pull insted of Fetch and Merge"</h1>
             <div  id="app">{{msg}}</div>
                    <p> welcome</p>
                    <p>Hi  there</p>
       
        <div><img src="youngLuffy.png" alt="HI There!" style="width: 45%"></div>
        <script>
            new Vue({
                el:"#app",
                data:{
                    msg:"hello"
                }
            })
        </script>
        </div>
    </body>
</html>
