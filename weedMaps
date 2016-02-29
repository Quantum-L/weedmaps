var w = jQuery( document ).width();
var diframe = '<iframe src="https://weedmaps.com/dispensaries/rocky-mountain-cannabis-2/menu/embed/" allowfullscreen webkitallowfullscreen mozallowfullscreen width="1170" height="1500" frameborder="0" scrolling="yes" marginheight="0" marginwidth="0"></iframe>';
var miframe = '<iframe src="https://mobile.weedmaps.com/#/dispensaries/rocky-mountain-cannabis-2/menu" allowfullscreen webkitallowfullscreen mozallowfullscreen width="1170" height="1500" frameborder="0" scrolling="yes" marginheight="0" marginwidth="0"></iframe>';

jQuery( document ).ready(function( $ ) {
if ( w < 768 ) {
 $( "#storeMenu" ).append( $( miframe ) );
}
else {
 $( "#storeMenu" ).append( $( diframe ) );
}
});