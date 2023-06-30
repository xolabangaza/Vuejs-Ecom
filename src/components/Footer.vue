<template>
<!-- <div class="footer">
    <h6>Footer</h6>
    <p class="footer-text-left">
        <routerlink class="menu" to="/">Home</routerlink>
        <routerlink class="menu" to="/">About</routerlink>
        <routerlink class="menu" to="/">Form</routerlink>
    </p>
</div>  -->
      <footer id="footer-sec">
        <div class="col">
           
        <div class="contact">
            <h4>Contact</h4>
            <p><strong>Address:</strong>Anywhere in Cape Town</p><br>
            <p><strong>Phone:</strong> 021 222 333 4</p>
        </div>
        <div class="hours">
            <h4>Operating hours</h4>
            <p><strong>Mon</strong>: 09:00 - 17:00</p>
            <p><strong>Tue</strong>: 09:00 - 17:00</p>
            <p><strong>Wed</strong>: 09:00 - 17:00</p>
            <p><strong>Thu</strong>: 09:00 - 17:00</p>
            <p><strong>Fri</strong>: 09:00 - 17:00</p>
            <p><strong>Sat</strong>: 09:00 - 15:00</p>


        </div>
            <div class="follow">
                <h4>Folow Us</h4>
                <div class="icon">
                    <i class="fab fa-youtube"></i>
                    <i class="fab fa-twitter mt-3"></i>
                    <i class="fab fa-facebook mt-3"></i>
                    <i class="fab fa-instagram mt-3"></i>
                </div>
            </div>
            <div class="links">
                <h4>Site links</h4>
                <ul>
                    <li><a href="./index.html">Home</a></li>
                    <li><a href="./assets/html/products.html">Product</a></li>
                    <li><a href="./assets/html/admin.html">About</a></li>
                    <li><a href="./assets/html/contact.html">Admin</a></li>
                    <li><a href="./assets/html/contact.html">Contact</a></li>
                    <li><a href="./assets/html/cart.html"><i class="far fa-shopping-bag"></i></a></li>
                   </ul>
                

            </div>


        </div>
        <div class="copyright">
            <p> copyright ©️ made by Xola Bangaza</p>
        </div>
      </footer>

</template>
<script>
export default {
    
}
</script>
<style scoped>


footer{
    background-color:rgb(189, 88, 177);
    color:gainsboro;
}

.col{
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    margin-right: 20px;

}

.follow{
    display: flex;
    flex-direction: column;
    margin-top: 40px;
}

.follow .icon{
    display: flex;
    flex-direction: column;
    justify-content: space-evenly;

}
.follow .icon:hover{
    color:blueviolet;
}

.contact{
    margin-top: 40px;
    margin-bottom: 40px;
    margin-left: 10px;
}


.copyright{
    color:blue;
    padding: 20px;
    justify-content: center;
    align-items: center;
    text-align: center;

}
.copyright:hover{
    color:blueviolet;
    
}
.hours{
    margin-top: 40px;
}

.links{
    margin-top: 40px;
}
.links li{
    list-style: none;
}
.links li:hover{
    background-color:blueviolet;
}


/* .footer {
    bottom: 0;
    left: 0;
    height: 90px;
    background-color:rgb(177, 167, 206);
}

.footer-text-left {
    font-size: 20px;
    padding-left: 40px;
    float: left;
    word-spacing: 20px;
    
}

.menu:hover {
    background-color:cornflowerblue;
    font-size:20px;
} */

</style>