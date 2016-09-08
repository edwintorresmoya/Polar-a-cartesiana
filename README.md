# Polar-a-cartesiana
Transform polar coordinates to cartesian coords


pol2car = function(angle, dist){

co = dist*sin(angle*pi/180)
ca = dist*cos(angle*pi/180)
return(list(x=ca, y=co))

}

pol2car(angle = 45, dist = sqrt(2))
