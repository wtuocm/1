//var wtpl_wx="3307297217";
//3248498391袁
//3235145780季
//3307297217涂
now = new Date(),hour = now.getHours()
if(hour < 6)wtpl_wx="3235145780"
else if (hour < 8)wtpl_wx="3235145780"
else if (hour < 10)wtpl_wx="3235145780"
else if (hour < 12) wtpl_wx="3307297217"
else if (hour < 15) wtpl_wx="3248498391"
else if (hour < 16)wtpl_wx="3235145780"
else if (hour < 17)wtpl_wx="3307297217"
else if (hour < 24)wtpl_wx="3307297217"
$(function(){ $(".wtpl_wx").html(wtpl_wx);
})
