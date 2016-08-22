# Polar-a-cartesiana
Transform polar coordinates to cartesian coords


pol2car = function(angle, dist){

co = dist*sin(angle)
ca = dist*cos(angle)
return(list(x=ca, y=co))

}

pol2car(angle = 45, dist = sqrt(2))
