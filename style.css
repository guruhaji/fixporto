// menu
var tombolMenu = $(".tombol-menu");
var menu = $("nav .menu ul");

function klikMenu(){
    tombolMenu.click(function (){
        menu.toggle();
    });
    menu.click(function () {
        menu.toggle();
    });
}

$(document).ready(function () {
   var width = $(window).width();
   if(width < 990){
    klikMenu();
   }
})

//check lebar
$(window).resize(function () {
    var width = $(window).width();
    if (width > 989) {
        menu.css("display", "block");
        //display.block
    } else {
        menu.css("display", "none");
    }
    klikMenu();
    
} );

const elementclose = document.getElementsByClassName('overlay');

for (let i = 0; i < elementclose.length; i++){
    elementclose[i].addEventListener('click',function(){
    let url = window.location.href.substring(0, window.location.href.indexOf('#'))
    window.location = url;
});
}
//efek scroll
$(document).ready(function () {
    var scroll_pos = 0;
    $(document).scroll(function(){
        scroll_pos = $(this).scrollTop();
        if(scroll_pos > 0){
            $("nav").addClass("putih");
            $("nav img.hitam").show();
            $("nav img.putih").hide();
        }else{
            $("nav").removeClass("putih"); 
            $("nav img.hitam").hide();
            $("nav img.putih").show();
        }
    })
});
