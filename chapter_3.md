# chapter 3:  
Gaussian filter = family of recursive state estimators. 

<img src="https://latex.codecogs.com/gif.latex?p(x)&space;=&space;det(2\pi&space;\Sigma&space;)^{-\frac{1}{2}}\exp&space;{\left&space;\{&space;-\frac{1}{2}\left&space;(&space;x-\mu&space;\right&space;)^{T}\Sigma&space;^{-1}\left&space;(&space;x-\mu&space;\right&space;)\right&space;\}}" title="p(x) = det(2\pi \Sigma )^{-\frac{1}{2}}\exp {\left \{ -\frac{1}{2}\left ( x-\mu \right )^{T}\Sigma ^{-1}\left ( x-\mu \right )\right \}}" />

• Chapter 3.2 describes the Kalman filter, which implements the Bayes filter  
  using the moments parameterization for a restricted class of problems 
  with linear dynamics and measurement functions. 
  
• The Kalman filter is extended to nonlinear problems in Chapter 3.3, which 
describes the extended Kalman filter. 

• Chapter 3.4 describes a different nonlinear Kalman filter, known as unscented Kalman filter.  

• Chapter 3.5 describes the information filter, which is the dual of theKalman filter using the canonical parameterization of Gaussians.  
