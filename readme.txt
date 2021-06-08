
imagename='img177.png' % image is given in the folder



***************When neither block size nor artifact position are known****************

Q= Q_P_u_S_u(imagename) % function to compute strength of blockiness  and given in the folder

% Q is the  quality score of the compressed image

% The value of Q is higher for more compressed image

***************************************************************************


***************When block size is known (8x8) and  artifact position is  unknown****************

Q= Q_P_u_S_k(imagename) % function to compute strength of blockiness  and given in the folder

% Q is the  quality score of the compressed image

% The value of Q is higher for more compressed image

************************************************************************************

***************When block size is known (8x8) and  artifact position is known (artifact at 8th position)****************

Q= Q_P_k_S_k(imagename) % function to compute strength of blockiness  and given in the folder

% Q is the  quality score of the compressed image

% The value of Q is higher for more compressed image

************************************************************************************

