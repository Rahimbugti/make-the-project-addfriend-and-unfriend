# make-the-project-addfriend-and-unfriend

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="smrt.css">
</head>
<body> 
    <div class="card">
        <img src="https://images.unsplash.com/photo-1747134392051-5e112c58ce1e?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxmZWF0dXJlZC1waG90b3MtZmVlZHw0fHx8ZW58MHx8fHx8" alt="">
        <h1>paris country</h1>
        <h5>Stranger</h5>
       
            <button class="add">Add Friend</button>
           
    </div>
    <script src="hdh.js"></script>
    
</body>
</html>



css  

 *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Georgia, 'Times New Roman', Times, serif;
 }
 html,body{
    height: 100%;
    width: 100%;
 }
 body {
    background-color: cornflowerblue;
    align-items: center;
    display: flex;
    justify-content: center;
 }
 .card{
    height: 400px;
    width: 300px;
    background-color: yellow;
    padding: 30px;
    align-items: center;
 }
 .card img{
    height: 50%;
    width: 100%;
    object-fit: cover;
    object-position: center;
    padding: 20px;
    border-radius: 10px;
 }
 .card h1{
    font-size: 30px
        
 }
 .card h5{
    font-size: 25px;
    color: darkcyan;
    padding-bottom:25px;
    margin-top: 20px ;
    margin-left: 20px;
    
 }
 .card button{
    background-color: cadetblue;
    color: white;
    font-weight: 700;
    padding: 5px 10px;
    border: none;
    border-radius: 50px;
    cursor: pointer;
    padding: 10px 20px;

 }
 .card .Remove{
    background-color: #dadada;
    color: black;
 }




javacript 




   var istatus = document.querySelector("h5")
var addFriend = document.querySelector(".add")
var RemoveFriend = document.querySelector(".add")
var check = 0;

addFriend.addEventListener("click",function(){
    if(check==0){
        istatus.innerHTML="friend";
    istatus.style.color="green";
    addFriend.innerHTML="Remove friend";
    check=1;  
    }
    else{
        istatus.innerHTML="Stranger";
        istatus.style.color="red";
        addFriend.innerHTML="Add friend";
        check=0;
    }
 
})





