## Learning to learn a hand deformation model 

## The overall loss function should look something like this: lambda_1*affine_transform_hand + lambda_2*movement_fingers.
   The idea is model the affine transform of the hand rotation separate and onto of that we movement of fingers. (Then rotated as well)
   

## 1) have a blender or mesh based simulation describing the motion. (example: rotation). Generate the mesh video. 
      Use this as guidance to drive the deformation for the real video motion.
      Then use this robotic hand to get the required mapping
   2) https://arxiv.org/pdf/2008.04451.pdf
        
