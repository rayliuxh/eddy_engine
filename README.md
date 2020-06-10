# Eddy Engine Ver. 01 (one single eddy) 

## code for making one eddy

The file for one eddy is "user_initialization.F90_000001" in MOM6-examples/src/MOM6/src/user

code for the interface 

     h(I,j,3) = 3200.0+400.0*exp(-((G%geoLonT(I,j)-30.0)**2+(G%geoLatT(I,j)-30.0)**2)/0.1)
     h(I,j,2) = 400.0 -400.0*exp(-((G%geoLonT(I,j)-30.0)**2+(G%geoLatT(I,j)-30.0)**2)/0.1)
     h(I,j,1) = 400.0