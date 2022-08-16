
imagename='img177.png' % image is given in the folder



(1) ***************Algorithm proposed in the paper****************

Q= Q_P_u_S_u(imagename) % function to compute strength of blockiness  and given in the folder

% Q is the  quality score of the compressed image

% The value of Q is higher for more compressed image

***************************************************************************


The following two methods (2) and (3) are additional for scenarios other than discussed in the paper. 

(2) ***************When block size is known (8x8) and  artifact position is  unknown****************

Q= Q_P_u_S_k(imagename) % function to compute strength of blockiness  and given in the folder

% Q is the  quality score of the compressed image

% The value of Q is higher for more compressed image

************************************************************************************

(3)***************When block size is known (8x8) and  artifact position is known (artifact at 8th position)****************

Q= Q_P_k_S_k(imagename) % function to compute strength of blockiness  and given in the folder

% Q is the  quality score of the compressed image

% The value of Q is higher for more compressed image

************************************************************************************

