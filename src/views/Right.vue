<template>

<!-- Header of the page  -->

    <div class="main">
          <div class="container">
        <div class="card">
            <div class="card-left">
                <div class="icon-wrapper" style="background-color: #fee7cc;">
                    <span class="material-icons">
                        <i class="fa fa-book" aria-hidden="true"></i>
                        
                    </span>
                </div>
                <div class="content-wrapper">
                    <div class="title">Articles Posted</div>
                    <div class="subtitle">80</div>
                </div>
            </div>
            <div class="card-right">
                <span class="material-icons">
                    <i class="fa fa-arrow-right" aria-hidden="true"></i>
                </span>
            </div>
        </div>
        <div class="card">
            <div class="card-left">
                <div class="icon-wrapper" style="background-color: #d8ddfa;">
                    <span class="material-icons">
                        
                        <i class="fa fa-handshake-o" aria-hidden="true"></i>
                    </span>
                </div>
                <div class="content-wrapper">
                    <div class="title">Claps This Week</div>
                    <div class="subtitle">1.5K</div>
                </div>
            </div>
            <div class="card-right">
                <span class="material-icons">
                    <i class="fa fa-arrow-right" aria-hidden="true"></i>
                </span>
            </div>
        </div>
        <div class="card">
            <div class="card-left">
                <div class="icon-wrapper" style="background-color: #e5e5e5;">
                    <span class="material-icons" style="font-size: 24px;">
                        <i class="fa fa-users" aria-hidden="true"></i>
                    </span>
                </div>
                <div class="content-wrapper">
                    <div class="title">New Followers This Week</div>
                    <div class="subtitle">972</div>
                </div>
            </div>


            <!-- Followers and stuff -->
        

        <!-- Footer of the Right Side of the web page -->
            
            <div class="card-right">
                <span class="material-icons">
                    <i class="fa fa-arrow-right" aria-hidden="true"></i>
                </span>
            </div>
        </div>
        <div class="banner">
            <span class="description">Buy <span class="emphasis">Pro Account</span>
                to Explore Premium Features</span>
            <button class="button1">
                Purchase Now
            </button>
            
        </div>
    </div>
    </div>
</template>
<style scoped>
button {
  all: unset;
}

button:hover,
button:focus {
  background: #333;
}
button:active {
  transform: scale(0.99);
}

.container {
  display: flex;
  flex-direction: column;
  margin-top: 50px;
  margin-left: auto;
  margin-right: auto;
  width: 70%;
  height: 500px;
  background-color: #f7f7f7;
  padding: 30px;
  border-radius: 25px;
}

.card {
  width: 100%;
  height: 70px;
  background-color: white;
  border-radius: 15px;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  padding: 15px;
  box-sizing: border-box;
  margin-bottom: 30px;
  -webkit-box-shadow: 0px 1px 1px 1.5px rgba(0, 0, 0, 0.12);
  -moz-box-shadow: 0px 1px 1px 1.5px rgba(0, 0, 0, 0.12);
  box-shadow: 0px 1px 1px 1.5px rgba(0, 0, 0, 0.12);
}

.card > .card-left {
  width: auto;
  height: auto;
  display: flex;
  flex-direction: row;
}

.card > .card-left > .icon-wrapper {
  width: 40px;
  height: 40px;
  border-radius: 10px;
  margin-right: 10px;
  display: flex;
  justify-content: center;
  align-items: center;
}

.card > .card-left > .content-wrapper {
  display: flex;
  flex-direction: column;
}

.title {
  font-size: 14px;
  font-family: "Lato", sans-serif;
}

.subtitle {
  font-size: 20px;
  font-family: "Lato", sans-serif;
  font-weight: 700;
}

.card > .card-right {
  background-color: #efefef;
  align-self: center;
  border-radius: 10px;
  display: flex;
  justify-content: center;
}

.banner {
  flex: 1;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  background-color: white;
  margin-top: 30px;
  border-radius: 20px;
}

.banner > .description {
  font-family: "Lato", sans-serif;
  color: #a7a7a7;
  margin: 0px 20% 0px;
  text-align: center;
  overflow: hidden;
}

.emphasis {
  color: black;
  font-weight: 700;
}

.button1 {
  margin-top: 20px;
  border-width: 0px;
  background-color: black;
  color: white;
  font-family: "Lato", sans-serif;
  padding: 10px 15px;
  border-radius: 8px;
}
.main{
    position: relative;
    bottom: 780px;
    left: 950px;
    width: 40%;
}
.img{
    border-radius: 30%;
}

</style>