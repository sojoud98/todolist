$("ul").on("click","span",function(event){
  $(this).parent().fadeOut(300,function(){
    $(this).remove();
    event.stopPropagation();
  })
});
$("ul").on("click","li",function(event){
  $(this).toggleClass("completed");
  event.stopPropagation();

})


$("input[type='text']").keypress(function(eve){
  if(eve.which===13){
    var elem= $("input").val();
    $("ul").append("<li><span><i class='far fa-trash-alt'></i></span> " +elem+"</li>");
  }
})
$(".fa-plus").on("click",function(){
  $("input[type='text']").fadeToggle(200);
})
