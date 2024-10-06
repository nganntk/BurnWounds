# BurnWounds

This paper is accepted to International Conference on Medical Image Computing and Computer Assisted Intervention (MICCAI) - Clinical Image-based Procedures (CLIP), 2024.

[[Paper]](https://doi.org/10.1007/978-3-031-73083-2_6) [[Free Download]](https://www.dropbox.com/scl/fi/xat6iwf3hicc7i16ocsv7/20240723_MICCAICLIP_BurnWounds.pdf?rlkey=ekxi51xlrngp1z6qkzpzd90jl&dl=0)

## Abstract
In the treatment of burn wounds, an accurate estimation of the ratio of the wound’s area to the total body surface area (%TBSA) is crucial. Medical doctors use %TBSA as one of the factors to determine the initial treatment, track the healing process, and devise subsequent treatments. Existing works estimate the %TBSA using generic human models with predefined percentages for each body part. These generic human models do not consider the patients’ actual body shape. Furthermore, the estimation of wound size depends greatly on the doctor’s experience, resulting in inaccurate estimated %TBSA. This work addresses the problem by using 3D modeling techniques and machine learning to give a better estimation of %TBSA for each individual patient. We do this by training a regressor to predict the patient’s body surface area from images of his face and hand, and by using a portable 3D scanner to determine the wound’s area. Our method estimates %TBSA with an average error of 8.5%, which is a huge improvement over the 140% error produced by existing methods. Our method is also easily accessible since it uses commercial-off-the-shelf (COTS) devices. This makes it practical for anyone, even those without medical knowledge, to use. Project page: https://github.com/nganntk/BurnWounds.

## Data and Code
Data and code will be updated soon. Stay tune!
