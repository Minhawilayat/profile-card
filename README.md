# profile-card
    <div class="profile-card">
       <div class="image">
     <img class="profile-img" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSMDCosTjdA91u3hKK1rq2zNa4Bdat3B8KTrw&s" height="150px" width="150px" alt="">
        </div>
   <div class="text-data">
    <span class="name">Minha</span>
    <span class="name">Coding Girl</span>
    <span class="job"><b>STUDENT AT SMIT</b></span>
  </div>

  <div class="media-buttons  ">
    <a href="#" style="background: #4267b2;" class="link">
      <i class="bx bxl-facebook"></i>
    </a>
    <a href="#"  style="background: #1da1f2;" class="link">
      <i class="bx bxl-twitter"></i>
    </a>
    <a href="#"  style="background: #e1306c;" class="link">
      <i class="bx bxl-instagram"></i>
    </a>
    <a href="#"  style="background: #ff0000;" class="link">
      <i class="bx bxl-youtube"></i>
    </a>
  </div>

  <div class="buttons">
    <button class="button">Subscribe</button>
    <button class="button">Messege</button>     
</div>

<div class="analytics">
<div class="data">
 <a href=""><i class="bx bx-heart"></i></a> 
 <span class="number">70k</span>
</div>
<div class="data">
  <a href="">   <i class="bx bx-message-rounded"></i></a>
<span class="number">24k</span>
</div>
<div class="data">
  <a href=""><i class="bx bx-share"></i></a>
<span class="number">13k</span>
        </div>
    </div>
</div>
<!---css--->
<style>
/* google fonts */
@import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');

*{
    font-family: "poppins" sans-serif;
margin: 0;
    padding: 0;
box-sizing: border-box;
}
body{
    height: 100vh;
    display: flex;   
    align-items: center;
    justify-content: center;
    background-color: #d5dae1;   
}
.profile-card{
    display:grid;
    max-width: 400px;
 height: 540px;
    width: 100%;
    background: #fff;
    padding: 25px ;
    box-sizing: 0 5px 10px rgba(0, 0, 0, 0.1  );
position: relative;
justify-content: center;
border-radius: 25px;

}
.profile-card::before{
content:'' ;
position: absolute;
top: 0;
left: 0;
height:30% ;
width: 100%;
background-image: url('https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSu-FUbeIonBT7ogb0NyRtNrkc1tArLFz5Mdg&s');
background-repeat: no-repeat;
background-size: cover;
border-radius: 24px 24px 0 0;
}
.image{margin: 25px  10px 0 55px ;
  position: relative;
   height: 170px;
   width:170px ; 
   border-radius: 50%;
   background-color: #4070f4;
   padding: 3px;
}
.profile-img{
height: 100%;
width: 100%;
object-fit:cover;
border-radius: 50%;
border:3px solid #fff ;
}
.text-data{
    display:flex;
    flex-direction:column ;
    align-items: center;

}
.name{
    font-size: 29px;
    font-weight: 600;
    margin-bottom: 5px;

}
.job{
    font-size: 15px;
    font-weight: 400;

}
.media-buttons{
display: flex;
align-items: center;
margin-top: 15PX;
justify-content: space-around;
}
.link{

    display: flex;
    align-items: center;
    justify-content: center;
    color: #fff;
    font-size: 18px;
    height: 34px;
    width: 34px;
    border-radius: 50%;
    margin: 0 8px;
    background-color:#4070f4 ;
    text-decoration: none;
}
.buttons{
    display: flex;
    align-items: center;
    margin-top: 25px;
    justify-content: center;
}
.button{
    color: #fff;
    font-size:14px ;
    font-weight: 400;
    border : none;
    border-radius: 24px ;
    margin: 0 10px ;
    padding: 8px 24px;
    background-color: #4070f4;
cursor:pointer;
transition:all 0.3s ease;

background-color: #4070f4;
}
.button:hover{
    background-color: #8e4bf1;
}
.analytics{
    display: flex;
    align-items: center;
    margin-top: 25px;
}
.data{
    display: flex;
    align-items: center;
   color: #333;
   padding: 0 20px;
   border-right: 2px solid #e7e7ee;
}
.data i {
font-size:20px ;
margin-right: 6px;
}
.data:last-child{
    border-right: none;
}
</style>
