<template>
  <div class="footer">
  <div class="footerInfo" style="background-color:#282828!important">
      <div class="AddressInfo">
        <img class="mt-3 mr-3 mb-3" style="width:25px" src="../assets/MiniLogo.png">
        <p class="mr-3">{{footerInfo}}</p>
        <p class="mr-3">{{footerAddress}}</p>
        <p class="mr-3">{{footerPhone}}</p>
        <p class="mr-3">{{footerEmail}}<span style="font-size: 1.2em; color: #eeeeee; font-family: Calibri">info@carpino.ir</span></p>
      </div>
      <div class="mt-5 Sponsers">
          <a href="https://www.cyberpolice.ir/" class="col-4"><img src="../assets/fata.png"></a>
          <a href="http://www.saramad.ir/" class="col-4"><img src="../assets/saramad.png"></a>
          <img class="col-md-4 serlogo m-2" id = 'jxlzwlaorgvjfukzjzpeapfu' style = 'border-radius: 50%; cursor:pointer' onclick = 'window.open("https://logo.samandehi.ir/Verify.aspx?id=143675&p=rfthaodsxlaogvkajyoedshw", "Popup","toolbar=no, scrollbars=no, location=no, statusbar=no, menubar=no, resizable=0, width=450, height=630, top=30")' alt = '' src = 'https://logo.samandehi.ir/logo.aspx?id=143675&p=nbpdshwlqftiwlbqyndtujyn' />
      </div>
  </div>
    <div class="privacy d-flex flex-row-reverse justify-content-between mt-2 mb-2 ml-5">
          <p class="mt-2 mr-5" style="color: dimgray">کلیه حقوق مادی و معنوی این سامانه به همراه اپلیکیشن ها متعلق به شرکت کارپینو می باشد</p>
          <div class="SocialNetworks">
            <a href="https://t.me/carpino" class="col-3"><img src="../assets/telegram.png"></a>
            <a href="https://www.instagram.com/carpino_app/" class="col-3"><img src="../assets/instagram.png"></a>
            <a href="https://www.linkedin.com/company/carpino/?trk=top_nav_home" class="col-3"><img src="../assets/linkedin.png"></a>
            <a href="https://twitter.com/carpino_app/" class="col-3"><img src="../assets/Tweeter.png"></a>
          </div>
        </div>
  </div>
</template>

<script>
  export default {
    components: {
    },
    props: {

    },
    data () {
      return {
        footerInfo:'اپلیکیشن درخواست تاکسی های رسمی شهر',
        footerAddress: 'خیابن آزادی، نرسیده به میدان انقلاب،ابتدای خیابان بهزاد، جنب سازمان تاکسیرانی، طبقه ۸ پارکینگ کاوه',
        footerPhone:'تلفن :  ۰۲۱۵۳۸۵۰۱۱۱ - پشتیبانی : ۱۸۰۰  ',
        footerEmail: ' ایمیل: ',
        };
    },
    methods: {

    }
}
</script>

<style scoped>
  @import "../assets/font/font-awesome-4.7.0/css/font-awesome.css";
  @import "../assets/font/font-awesome-4.7.0/css/font-awesome.min.css";
  @import "https://maxcdn.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css";
  @import "https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css";
  @import "https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap-theme.min.css";
  @import "https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css";

/*footer*/
.footer{
  background-color: black;
  font-family: iranyekan;
}
.footerInfo p{
  color: #eeeeee;
  font-family: iranyekan;
  direction: rtl;
  text-align: right;
  font-size: 0.7em;
}

.privacy p{
  font-size: 0.7em;
}
.footerInfo{
  display: flex;
  flex-direction: row-reverse;
  justify-content: space-between;
}

.AddressInfo{
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-end;
}
@media (min-width: 240px) and (max-width: 768px) {
  .footerInfo{
    display: flex;
    flex-direction: column-reverse;
  }
  .AddressInfo{
    display: flex;
    flex-direction: column;
    justify-content: flex-end;
    align-items: flex-end;
  }
  .footer p{
    font-size: 7px;
  }

  .footer span{
    font-size: 55px;
  }
  .SocialNetworks{
    display: none;
    visibility: hidden;
  }
  .privacy p{
    font-size: 0.45em;
    text-align: center;
  }
  .Sponsers{
    display: flex;
    margin-left: 12px;
    flex-direction: row;
    text-align: center;
  }
}

.SocialNetworks img{
  width: 1.4em;
}
.Sponsers img{
  width: 3.8em;
}
.serlogo{
  height: 4em;
  width:  4em;
  cursor:pointer;
  background-color: #fff;
  border-radius: 50%
}

</style>
