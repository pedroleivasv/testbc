$(function () {
    "use strict";
    $.scrollIt({
	easing: 'swing',
	scrollTime: 900,
	activeClass: 'active',
	onPageChange: null,
	topOffset: -70,
	upKey: 38,
        downKey: 40
	  });
    $(document).scroll(function () {
        var $nav = $("#mainNavbar");
        $nav.toggleClass("scrolled", $(this).scrollTop() > $nav.height());
    });
    $(document).on('click',function(){ 
    $('.navbar .collapse').collapse('hide');})
});
